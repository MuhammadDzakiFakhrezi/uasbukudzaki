<template>
  
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact from app</title>
    <link
      href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css"
      rel="stylesheet"
    />
    
</head>
<body>

    <section class="text-gray-600 body-font">
        <form id="contact-form" 
              action="https://formspree.io/f/xpzeovjj" 
              method="POST">
          <div class="container px-5 py-24 mx-auto">
          <div class="flex flex-col text-center w-full mb-12">
            <lord-icon
            src="https://assets10.lottiefiles.com/packages/lf20_lshv4smz.json"
            trigger="hover"
            style="width: 1450px; height: 150px"
            class="hidden lg:flex"></lord-icon>
            <h1 class="sm:text-3xl text-2xl font-medium title-font mb-4 text-gray-900">Kontak Saya

            </h1>
            <p class="lg:w-2/3 mx-auto leading-relaxed text-base">
                Terima kasih, Mohon Hubungi Kontak Saya Jika ada kesalahan dalam penggunaan aplikasi ;) .
           </p>
          </div>
          <div class="lg:w-1/3 w-full mx-auto px-8">
            <div class="relative flex-grow w-full">
              <label for="full-name" class="leading-7 text-sm text-gray-600"
                >Nama Pengirim</label
              >
              <input
                type="text"
                id="full-name"
                name="full-name"
                class="w-full bg-white bg-opacity-50 rounded border 
                border-gray-300 focus:border-red-500 focus:bg-transparent 
                focus:ring-2 focus:ring-red-200 text-base outline-none 
                text-gray-700 py-1 px-3 leading-8 transition-colors 
                duration-200 ease-in-out"
              />
            </div>
            <div class="relative flex-grow w-full">
              <label for="email" class="leading-7 text-sm text-gray-600"
                >Email Pengirim</label
              >
              <input
                type="email"
                id="email"
                name="email"
                class="w-full bg-white bg-opacity-50 rounded border border-gray-300 focus:border-red-500 focus:bg-transparent focus:ring-2 focus:ring-red-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
              />
            </div>
            <div class="relative flex-grow w-full">
              <label for="subject" class="leading-7 text-sm text-gray-600"
                >Subjek</label
              >
              <input
                type="text"
                id="subject"
                name="subject"
                class="w-full bg-white bg-opacity-50 rounded border border-gray-300 focus:border-red-500 focus:bg-transparent focus:ring-2 focus:ring-red-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
              />
            </div>
            <div class="relative flex-grow w-full">
              <label for="message" class="leading-7 text-sm text-gray-600"
                >Pesan</label
              >
              <textarea
                type="text"
                id="message"
                name="message"
                class="w-full bg-white bg-opacity-50 rounded border border-gray-300 focus:border-red-500 focus:bg-transparent focus:ring-2 focus:ring-red-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
              ></textarea>
            </div>
            <button
             type="submit" 
            id="iniaja" class="mt-3 w-full text-light bg-yellow-500 border-0 py-2 px-8 
            focus:outline-none hover:bg-yellow-600 rounded text-lg">
            Kirim pesan
           </button>
          </div>
          </div>
        </form>
    </section>
    
</body>


</template>

<script>

</script>

<style>



#iniaja {
  background-color: #3B3B3B;
}
</style>
