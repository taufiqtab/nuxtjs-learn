<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        About {{angka}}
      </h1>
      <p v-if="$fetchState.pending">Mengambil gunung...</p>
      <p v-else-if="$fetchState.error">Terjadi kegalatan :(</p>


      <ul v-for="data of datas.data" :key="data.id">
        <li>{{ data.name }}</li>
      </ul>

      <br /><br />
      <!-- <button @click="$fetch">Segarkan</button> -->
      <a @click="$fetch" target="_blank" rel="noopener noreferrer" class="button--grey">
        Segarkan
      </a>

      <!-- <button v-on:click="gantiAngka">Ganti Angka</button> -->

      <a v-on:click="gantiAngka" target="_blank" rel="noopener noreferrer" class="button--grey">
        Ganti Angka
      </a>

      <div class="links">

      </div>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Judul situs web saya',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: 'Deskripsi untuk website saya'
      }
    ],
    link: [{ rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }]
  },
   data() {
      return {
        datas: [],
        angka : "1",
        terganti : false
      }
    },
    async fetch() {
      this.datas = await fetch(
        'https://reqres.in/api/unknown'
      ).then(res => res.json())
    },
    methods: {
    gantiAngka: function () {
      if(this.terganti == false)
        this.angka = "Terganti"
      if(this.terganti == true)
        this.angka = "1"
      
      this.terganti = !this.terganti;
    }
  }
    
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
