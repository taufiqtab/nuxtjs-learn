<template>
  <div>
    <div>
      <h1>
        Dashboard
      </h1>
      <div class="min-h-screen flex items-start justify-center">
    <div class="bg-white p-4 rounded w-full">
  
        <div class="md:grid md:grid-cols-3 md:gap-4 space-y-4 md:space-y-0 mt-4">
            <div class="shadow border rounded-lg">
                <div class="flex items-center space-x-4 p-4">
                    <div class="flex items-center p-4 bg-purple-600 text-white rounded-lg">
                        <svg xmlns="http://www.w3.org/2000/svg" class="fill-current w-7 h-7" width="24" height="24" viewBox="0 0 24 24"><path d="M17.997 18h-11.995l-.002-.623c0-1.259.1-1.986 1.588-2.33 1.684-.389 3.344-.736 2.545-2.209-2.366-4.363-.674-6.838 1.866-6.838 2.491 0 4.226 2.383 1.866 6.839-.775 1.464.826 1.812 2.545 2.209 1.49.344 1.589 1.072 1.589 2.333l-.002.619zm4.811-2.214c-1.29-.298-2.49-.559-1.909-1.657 1.769-3.342.469-5.129-1.4-5.129-1.265 0-2.248.817-2.248 2.324 0 3.903 2.268 1.77 2.246 6.676h4.501l.002-.463c0-.946-.074-1.493-1.192-1.751zm-22.806 2.214h4.501c-.021-4.906 2.246-2.772 2.246-6.676 0-1.507-.983-2.324-2.248-2.324-1.869 0-3.169 1.787-1.399 5.129.581 1.099-.619 1.359-1.909 1.657-1.119.258-1.193.805-1.193 1.751l.002.463z"/></svg>
                    </div>
                    <div class="flex-1">
                        <p class="text-gray-500 font-semibold">Total Service Request</p>
                        <div class="flex items-baseline space-x-4">
                            <h2 class="text-2xl font-semibold">
                                34,567
                            </h2>
                            <p class="text-green-700 flex font-semibold space-x-1">
                                <span>&#8593;</span>
                                <span class="font-bold">122</span>
                            </p>
                        </div>
                    </div>
                </div>
                <a href="#" class="block p-3 text-lg font-semibold bg-purple-50 text-purple-800 hover:bg-purple-100 cursor-pointer">
                    View all
                </a>
            </div>
            <div class="shadow border rounded-lg">
                <div class="flex items-center space-x-4 p-4">
                    <div class="flex items-center p-4 bg-purple-600 text-white rounded-lg">
                        <svg xmlns="http://www.w3.org/2000/svg" class="fill-current w-7 h-7" width="24" height="24" viewBox="0 0 24 24"><path d="M17.997 18h-11.995l-.002-.623c0-1.259.1-1.986 1.588-2.33 1.684-.389 3.344-.736 2.545-2.209-2.366-4.363-.674-6.838 1.866-6.838 2.491 0 4.226 2.383 1.866 6.839-.775 1.464.826 1.812 2.545 2.209 1.49.344 1.589 1.072 1.589 2.333l-.002.619zm4.811-2.214c-1.29-.298-2.49-.559-1.909-1.657 1.769-3.342.469-5.129-1.4-5.129-1.265 0-2.248.817-2.248 2.324 0 3.903 2.268 1.77 2.246 6.676h4.501l.002-.463c0-.946-.074-1.493-1.192-1.751zm-22.806 2.214h4.501c-.021-4.906 2.246-2.772 2.246-6.676 0-1.507-.983-2.324-2.248-2.324-1.869 0-3.169 1.787-1.399 5.129.581 1.099-.619 1.359-1.909 1.657-1.119.258-1.193.805-1.193 1.751l.002.463z"/></svg>
                    </div>
                    <div class="flex-1">
                        <p class="text-gray-500 font-semibold">Total Open</p>
                        <div class="flex items-baseline space-x-4">
                            <h2 class="text-2xl font-semibold">
                                34,567
                            </h2>
                            <p class="text-green-700 flex font-semibold space-x-1">
                                <span>&#8593;</span>
                                <span class="font-bold">122</span>
                            </p>
                        </div>
                    </div>
                </div>
                <a href="#" class="block p-3 text-lg font-semibold bg-purple-50 text-purple-800 hover:bg-purple-100 cursor-pointer">
                    View all
                </a>
            </div>
            <div class="shadow border rounded-lg">
                <div class="flex items-center space-x-4 p-4">
                    <div class="flex items-center p-4 bg-purple-600 text-white rounded-lg">
                        <svg xmlns="http://www.w3.org/2000/svg" class="fill-current w-7 h-7" width="24" height="24" viewBox="0 0 24 24"><path d="M17.997 18h-11.995l-.002-.623c0-1.259.1-1.986 1.588-2.33 1.684-.389 3.344-.736 2.545-2.209-2.366-4.363-.674-6.838 1.866-6.838 2.491 0 4.226 2.383 1.866 6.839-.775 1.464.826 1.812 2.545 2.209 1.49.344 1.589 1.072 1.589 2.333l-.002.619zm4.811-2.214c-1.29-.298-2.49-.559-1.909-1.657 1.769-3.342.469-5.129-1.4-5.129-1.265 0-2.248.817-2.248 2.324 0 3.903 2.268 1.77 2.246 6.676h4.501l.002-.463c0-.946-.074-1.493-1.192-1.751zm-22.806 2.214h4.501c-.021-4.906 2.246-2.772 2.246-6.676 0-1.507-.983-2.324-2.248-2.324-1.869 0-3.169 1.787-1.399 5.129.581 1.099-.619 1.359-1.909 1.657-1.119.258-1.193.805-1.193 1.751l.002.463z"/></svg>
                    </div>
                    <div class="flex-1">
                        <p class="text-gray-500 font-semibold">Total Closed</p>
                        <div class="flex items-baseline space-x-4">
                            <h2 class="text-2xl font-semibold">
                                34,567
                            </h2>
                            <p class="text-green-700 flex font-semibold space-x-1">
                                <span>&#8593;</span>
                                <span class="font-bold">122</span>
                            </p>
                        </div>
                    </div>
                </div>
                <a href="#" class="block p-3 text-lg font-semibold bg-purple-50 text-purple-800 hover:bg-purple-100 cursor-pointer">
                    View all
                </a>
            </div>
        </div>
    </div>

</div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'admin',
  head: {
    title: 'Dashboard',
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
