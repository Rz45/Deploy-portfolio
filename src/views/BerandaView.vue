<template>
    <!-- Header Start -->
    <header class="bg-transparent absolute top-0 left-0 w-full flex items-center z-10">
      <div class="container">
        <div class="flex items-center justify-between relative">
          <div class="px-4">
            <a href="#home" class="font-bold text-lg text-primary block py-6">Rizky Aris Adzin</a>
          </div>
          <div class="flex items-center px-4">
            <button id="hamburger" name="hamburger" type="button" class="block absolute right-4 lg:hidden">
              <span class="hamburger-line transition duration-300 ease-in-out origin-top-left"></span>
              <span class="hamburger-line transition duration-300 ease-in-out"></span>
              <span class="hamburger-line transition duration-300 ease-in-out origin-bottom-left"></span>
            </button>

            <nav id="nav-menu" class="hidden absolute py-5 bg-white shadow-lg rounded-lg max-w-[250px] w-full right-4 top-full lg:block lg:static lg:bg-transparent lg:max-w-full lg:shadow-none lg:rounded-none">
              <ul class="block lg:flex">
                <li class="group">
                  <a href="#home" class="text-base text-dark py-2 mx-8 flex group-hover:text-primary">Beranda</a>
                </li>
                <li class="group">
                  <a href="#about" class="text-base text-dark py-2 mx-8 flex group-hover:text-primary">Tentang Saya</a>
                </li>
                <li class="group">
                  <a href="#clients" class="text-base text-dark py-2 mx-8 flex group-hover:text-primary">Clients</a>
                </li>
                <li class="group">
                  <a href="#blog" class="text-base text-dark py-2 mx-8 flex group-hover:text-primary">Blog</a>
                </li>
                <li class="group">
                  <a href="#contact" class="text-base text-dark py-2 mx-8 flex group-hover:text-primary">Contact</a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
      </div>
    </header>
    <!-- Header End -->

    <!-- Hero Section Start -->
    <section id="home" class="pt-36">
      <div class="container">
        <div class="flex flex-wrap">
          <div class="w-full self-center px-4 lg:w-1/2">
            <h1 class="text-base font-semibold text-primary md:text-xl">
              Halo Semua 👋, saya
              <span class="block font-bold text-dark text-4xl mt-1 lg:text-5-xl"
                >Rizky Aris Adzin</span
              >
            </h1>
            <h2 class="font-medium text-secondary text-lg mb-5 lg:text-2-xl">
              Mahasiswa & <span class="text-dark">Programmer</span>
            </h2>
            <p class="font-medium text-secondary mb-10 leading-relaxed">
              Belajar web programming sangat memusingkan bukan.
              <span class="text-dark font-bold">Yeah!</span>
            </p>

            <a
              href="#"
              class="text-base font-semibold text-white bg-primary py-3 px-8 rounded-full hover:shadow-lg hover:opacity-80 transition duration-300 ease-in-out"
              >Hubungi Saya</a
            >
          </div>
          <div class="w-full self-end px-4 lg:w-1/2">
            <div class="relative mt-10 lg:mt-0 lg:right-0">
              <img
                src="../img/sapiens.png"
                alt="Rizky"
                class="max-w-full mx-auto"
              />
              <span
                class="absolute -bottom-20 -z-10 left-1/2 -translate-x-1/2 md:scale-125"
              >
                <svg
                  width="400"
                  height="400"
                  viewBox="0 0 200 200"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill="#14b8a6"
                    d="M50.4,-60.4C59.4,-52.6,56.4,-31,56.8,-12.4C57.2,6.2,61,21.7,56.7,36.1C52.4,50.4,40.1,63.4,24.8,69.6C9.5,75.9,-8.9,75.4,-24.6,69C-40.2,62.6,-53.2,50.4,-65,35C-76.9,19.7,-87.7,1.2,-83.3,-13.1C-78.9,-27.4,-59.4,-37.4,-42.9,-43.9C-26.5,-50.3,-13.3,-53.2,3.7,-57.7C20.8,-62.2,41.5,-68.2,50.4,-60.4Z"
                    transform="translate(100 100) scale(1.1)"
                  />
                </svg>
              </span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Hero Section End -->

    <!-- About Section Start -->
    <section id="about" class="pt-36 pb-32">
      <div class="container">
        <div class="flex flex-wrap">
          <div class="w-full px-4 mb-10 lg:w-1/2">
            <h4 class="font-bold uppercase text-primary text-lg">Tentang Saya</h4>
            <h2 class="font-bold text-dark text-3-xl mb-5 max-w-md lg:text-4xl"></h2>
            <h2
              class="font-bold text-dark text-3-xl mb-5 max-w-md lg:text-4-xl"
            >
              Yuk, belajar web programming di WPU!
            </h2>
            <p class="font-medium text-base text-secondary max-w-xl lg:text-lg">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis
              consequatur at nostrum fuga numquam, aspernatur illum.
            </p>
          </div>
          <div class="w-full px-4 lg:w-1/2">
            <h3 class="font-semibold text-dark text-2xl mb-4 lg:text-3xl lg:pt-10">Mari Berteman</h3>
            <p class="font-medium text-base text-secondary mb-6 lg:text-lg">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Molestiae
              error, eos non deserunt quis pariatur asperiores veritatis quia
              nobis voluptate.
            </p>
            <div class="flex items-center">
              <!-- Youtube -->
              <a
                href="https://youtube.com/@Rizky-id5eb"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-slate-300 hover:border-primary hover:bg-primary hover:text-white"
              >
                <svg
                  role="img"
                  width="20"
                  class="fill-current"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>YouTube</title>
                  <path
                    d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"
                  />
                </svg>
              </a>
  
              <!-- Instagram -->
              <a
                href="https://instagram.com/rizkyarisa_"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-slate-300 hover:border-primary hover:bg-primary hover:text-white"
              >
                <svg
                  role="img"
                  width="20"
                  class="fill-current"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>Instagram</title>
                  <path
                    d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"
                  />
                </svg>
              </a>
  
              <!-- Facebook -->
              <a
                href="https://facebook.com/rizkyarisadzin"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-slate-300 hover:border-primary hover:bg-primary hover:text-white"
              >
                <svg
                  role="img"
                  width="20"
                  class="fill-current"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>Facebook</title>
                  <path
                    d="M9.101 23.691v-7.98H6.627v-3.667h2.474v-1.58c0-4.085 1.848-5.978 5.858-5.978.401 0 .955.042 1.468.103a8.68 8.68 0 0 1 1.141.195v3.325a8.623 8.623 0 0 0-.653-.036 26.805 26.805 0 0 0-.733-.009c-.707 0-1.259.096-1.675.309a1.686 1.686 0 0 0-.679.622c-.258.42-.374.995-.374 1.752v1.297h3.919l-.386 2.103-.287 1.564h-3.246v8.245C19.396 23.238 24 18.179 24 12.044c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.628 3.874 10.35 9.101 11.647Z"
                  />
                </svg>
              </a>
  
              <!-- Tiktok -->
              <a
                href="https://tiktok.com/rizky45"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-slate-300 hover:border-primary hover:bg-primary hover:text-white"
              >
                <svg
                  role="img"
                  width="20"
                  class="fill-current"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>TikTok</title>
                  <path
                    d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"
                  />
                </svg>
              </a>
              <!-- Facebook -->
              <a
                href="https:facebook.com/rizkyarisadzin"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-slate-300 hover:border-primary hover:bg-primary hover:text-white"
              >
                <svg
                  role="img"
                  viewBox="0 0 24 24"
                  width="20"
                  class="fill-current"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>Facebook</title>
                  <path
                    d="M9.101 23.691v-7.98H6.627v-3.667h2.474v-1.58c0-4.085 1.848-5.978 5.858-5.978.401 0 .955.042 1.468.103a8.68 8.68 0 0 1 1.141.195v3.325a8.623 8.623 0 0 0-.653-.036 26.805 26.805 0 0 0-.733-.009c-.707 0-1.259.096-1.675.309a1.686 1.686 0 0 0-.679.622c-.258.42-.374.995-.374 1.752v1.297h3.919l-.386 2.103-.287 1.564h-3.246v8.245C19.396 23.238 24 18.179 24 12.044c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.628 3.874 10.35 9.101 11.647Z"
                  />
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>
      
    </section>
    <!-- About Section End -->

    <!-- About Section End -->

    <!-- Portfolio Start -->
    <section id="portfolio" class="pt-36 pb-16 bg-slate-100">
      <div class="container">
        <div class="w-full px-4">
          <div class="max-w-xl mx-auto text-center mb-16">
            <h4 class="font-semibold text-lg text-primary mb-2">Portfolio</h4>
            <h2
              class="font-bold text-dark text-3xl mb-4 sm:text-4xl lg:text-5xl"
            >
              Project Terbaru
            </h2>
            <p class="font-medium tex-md text-secondary md:text-lg">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui aut
              quisquam excepturi voluptas! Id nam totam ab fugiat maxime! Velit?
            </p>
          </div>
        </div>
        <div
          class="w-full px-4 flex flex-wrap justify-center xl:w-10/12 xl:mx-auto"
        >
          <div class="mb-12 p-4 md:w-1/2">
            <div class="rounded-md shadow-md overflow-hidden">
              <img
                src="../img/portfolio/p1.png"
                alt="Landing Page"
                width="w-full"
              />
              <h3 class="font-semibold text-xl text-dark mt-5 mb-3">
                Undangan Pernikahan
              </h3>
              <p class="font-medium text-base text-secondary">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Voluptatem, ipsa!
              </p>
            </div>
          </div>
          <div class="mb-12 p-4 md:w-1/2">
            <div class="rounded-md shadow-md overflow-hidden">
              <img
                src="../img/portfolio/p2.png"
                alt="Landing Page"
                width="w-full"
              />
              <h3 class="font-semibold text-xl text-dark mt-5 mb-3">
                Parallax Website
              </h3>
              <p class="font-medium text-base text-secondary">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Voluptatem, ipsa!
              </p>
            </div>
          </div>
          <div class="mb-12 p-4 md:w-1/2">
            <div class="rounded-md shadow-md overflow-hidden">
              <img
                src="../img/portfolio/p3.png"
                alt="Landing Page"
                width="w-full"
              />
              <h3 class="font-semibold text-xl text-dark mt-5 mb-3">
                UTS Website
              </h3>
              <p class="font-medium text-base text-secondary">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Voluptatem, ipsa!
              </p>
            </div>
          </div>
          <div class="mb-12 p-4 md:w-1/2">
            <div class="rounded-md shadow-md overflow-hidden">
              <img
                src="../img/portfolio/p4.png"
                alt="Landing Page"
                width="w-full"
              />
              <h3 class="font-semibold text-xl text-dark mt-5 mb-3">
                Resepin Mobile App
              </h3>
              <p class="font-medium text-base text-secondary">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Voluptatem, ipsa!
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Portfolio End -->

    <!-- Clients Section Start -->
    <section id="clients" class="pt-36 pb-32 bg-slate-800">
      <div class="container">
        <div class="w-full px-4">
          <div class="w-full px-4">
            <div class="mx-auto text-center mb-16">
              <h4 class="font-semibold text-lg text-primary mb-2">Clients</h4>
              <h2 class="font-bold text-white text-3xl mb-4 sm:text-4xl lg:text-5xl">Yang Pernah Bekerja Sama</h2>
              <p class="font-medium text-md text-secondary md:text-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla aut consequuntur perferendis.</p>
            </div>
          </div>
        </div>

        <div class="w-full px-4">
          <div class="flex flex-wrap items-center justify-center">
            <a href="" class="max-w-[120px] mx-4 py-4 grayscale opacity-60 transition duration-500 hover:grayscale-0 hover:opacity-100 lg:mx-6 xl:x-8"> 
              <img src="../img/clients/Google_2015_logo.svg.png" alt="Google">
            </a>
            <a href="" class="max-w-[120px] mx-4 py-4 grayscale opacity-60 transition duration-500 hover:grayscale-0 hover:opacity-100 lg:mx-6 xl:x-8"> 
              <img src="../img/clients/Gojek_logo_2022.svg.png" alt="Gojek">
            </a>
            <a href="" class="max-w-[120px] mx-4 py-4 grayscale opacity-60 transition duration-500 hover:grayscale-0 hover:opacity-100 lg:mx-6 xl:x-8"> 
              <img src="../img/clients/Tokopedia.svg.png" alt="Tokopedia">
            </a>
            <a href="" class="max-w-[120px] mx-4 py-4 grayscale opacity-60 transition duration-500 hover:grayscale-0 hover:opacity-100 lg:mx-6 xl:x-8"> 
              <img src="../img/clients/640px-Riot_Games_wordmark.svg.png" alt="Riot Games">
            </a>
          </div>
        </div>
      </div>
    </section>
    <!-- Clients Section End -->

         <!-- Blog Section Start -->
    <section id="blog" class="pt-36 pb-32 bg-slate-100">
      <div class="container">
        <div class="w-full px-4">
          <div class="max-w-xl mx-auto text-center mb-16">
            <h4 class="font-semibold text-lg text-primary mb-2">Blog</h4>
            <h2 class="font-bold text-dark text-3xl mb-4 sm:text-4xl lg:text-5xl">Tulisan Terkini</h2>
            <p class="font-medium text-md text-secondary md:text-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus dolores optio soluta? Adipisci, incidunt.</p>
          </div>
        </div>
        
        <div class="flex flex-wrap">
          <div class="w-full px-4 lg:w-1/2 xl:w-1/3">
            <div class="bg-white rounded-xl shadow-lg overflow-hidden mb-10">
              <img src="https://source.unsplash.com/360x200?programming" alt="programming" class="w-full">
              <div class="py-8 px-6">
                <h3><a href="#" class="block mb-3 font-semibold text-xl text-dark hover:text-primary truncate">Tips Belajar Programming</a></h3>
                <p class="font-medium text-base text-secondary mb-6">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure, voluptate?</p>
                <a href="#" class="font-medium text-sm text-white bg-primary py-2 px-4 rounded-lg hover:opacity-80">Baca Selengkapnya</a>
              </div>
            </div>
          </div>
          <div class="w-full px-4 lg:w-1/2 xl:w-1/3">
            <div class="bg-white rounded-xl shadow-lg overflow-hidden mb-10">
              <img src="https://source.unsplash.com/360x200?food" alt="Food" class="w-full">
              <div class="py-8 px-6">
                <h3><a href="#" class="block mb-3 font-semibold text-xl text-dark hover:text-primary truncate">Delicious Food</a></h3>
                <p class="font-medium text-base text-secondary mb-6">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cum illum quaerat assumenda suscipit eligendi optio.</p>
                <a href="#" class="font-medium text-sm text-white bg-primary py-2 px-4 rounded-lg hover:opacity-80">Baca Selengkapnya</a>
              </div>
            </div>
          </div>
          <div class="w-full px-4 lg:w-1/2 xl:w-1/3">
            <div class="bg-white rounded-xl shadow-lg overflow-hidden mb-10">
              <img src="https://source.unsplash.com/360x200?game" alt="Gaming" class="w-full">
              <div class="py-8 px-6">
                <h3><a href="#" class="block mb-3 font-semibold text-xl text-dark hover:text-primary truncate">Tips Gaming</a></h3>
                <p class="font-medium text-base text-secondary mb-6">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam laboriosam maxime repellendus exercitationem nisi, molestias eius quia.</p>
                <a href="#" class="font-medium text-sm text-white bg-primary py-2 px-4 rounded-lg hover:opacity-80">Baca Selengkapnya</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Blog Section End -->

    <!-- Contact Section Start -->
    <section id="contact" class="pt-36 pb-32">
      <div class="container">
        <div class="w-full px-4">
          <div class="max-w-xl mx-auto text-center mb-16">
            <h4 class="font-semibold text-lg text-primary mb-2">Contact</h4>
            <h2 class="font-bold text-dark text-3xl mb-4 sm:text-4xl lg:text-5xl">Hubungi Saya</h2>
            <p class="font-medium text-md text-secondary md:text-lg">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolores perferendis ad commodi.</p>
          </div>
        </div>
      </div>

        <form>
          <div class="w-full lg:w-2/3 lg:mx-auto">
            <div class="w-full px-4 mb-8">
              <label for="name" class="text-base font-bold text-primary">Nama</label>
              <input type="text" id="name" class="w-full bg-slate-200 text-dark p-3 rounded-md focus:outline-none focus:ring-primary focus:ring-1 focus:border-primary">
            </div>
            <div class="w-full px-4 mb-8">
              <label for="email" class="text-base font-bold text-primary">Email</label>
              <input type="email" id="email" class="w-full bg-slate-200 text-dark p-3 rounded-md focus:outline-none focus:ring-primary focus:ring-1 focus:border-primary">
            </div>
            <div class="w-full px-4 mb-8">
              <label for="message" class="text-base font-bold text-primary">Pesan</label>
              <textarea type="email" id="email" class="w-full bg-slate-200 text-dark p-3 rounded-md focus:outline-none focus:ring-primary focus:ring-1 focus:border-primary h-32"></textarea>
            </div>
            <div class="w-full px-4">
              <button class="text-base font-semibold text-white bg-primary py-3 px-8 rounded-full w-full hover:opacity-80 hover:shadow-lg transition duration-500">Kirim</button>
            </div>
          </div>
        </form>
      </section>
      <!-- Contact Section End -->

      <!-- Footer Start -->
      <footer class="bg-dark pt-24 pb-12">
        <div class="container">
          <div class="flex flex-wrap">
            <div class="w-full px-4 mb-12 text-slate-300 font-medium md:w-1/3">
              <h2 class="font-bold text-4xl text-white mb-5">Kantor</h2>
              <h3 class="font-bold text-2xl mb-2">Hubungi Kami</h3>
              <p>rizkyarisadzin@gmail.com</p>
              <p>Jl. Murai No. 3</p>
              <p>Karawang</p>
            </div>
            <div class="w-full px-4 mb-12 md:w-1/3">
              <h3 class="font-semibold text-xl text-white mb-5">Kategori Tulisan</h3>
              <ul class="text-slate-300">
                <li>
                  <a href="#" class="inline-block text-base hover:text-primary mb-3">Programming</a>
                </li>
                <li>
                  <a href="#" class="inline-block text-base hover:text-primary mb-3">Teknologi</a>
                </li>
                <li>
                  <a href="#" class="inline-block text-base hover:text-primary mb-3">Makanan</a>
                </li>
              </ul>
            </div>
            <div class="w-full px-4 mb-12 md:w-1/3">
              <h3 class="font-semibold text-xl text-white mb-5">Tautan</h3>
              <ul class="text-slate-300">
                <li>
                  <a href="#home" class="inline-block text-base hover:text-primary mb-3">Beranda</a>
                </li>
                <li>
                  <a href="#about" class="inline-block text-base hover:text-primary mb-3">Tentang Saya</a>
                </li>
                <li>
                  <a href="#portfolio" class="inline-block text-base hover:text-primary mb-3">Portfolio</a>
                </li>
                <li>
                  <a href="#clients" class="inline-block text-base hover:text-primary mb-3">clients</a>
                </li>
                <li>
                  <a href="#blog" class="inline-block text-base hover:text-primary mb-3">Blog</a>
                </li>
                <li>
                  <a href="#contact" class="inline-block text-base hover:text-primary mb-3">Contact</a>
                </li>
              </ul>
            </div>
          </div>

          <div class="w-full pt-10 border-t border-slate-700">
            <div class="flex items-center justify-center mb-5">
              <!-- Youtube -->
              <a
                href="https://youtube.com/@Rizky-id5eb"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-slate-300 hover:border-primary hover:bg-primary hover:text-white"
              >
                <svg
                  role="img"
                  width="20"
                  class="fill-current"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>YouTube</title>
                  <path
                    d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"
                  />
                </svg>
              </a>
  
              <!-- Instagram -->
              <a
                href="https://instagram.com/rizkyarisa_"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-slate-300 hover:border-primary hover:bg-primary hover:text-white"
              >
                <svg
                  role="img"
                  width="20"
                  class="fill-current"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>Instagram</title>
                  <path
                    d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"
                  />
                </svg>
              </a>
  
              <!-- Facebook -->
              <a
                href="https://facebook.com/rizky.a.adzin"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-slate-300 hover:border-primary hover:bg-primary hover:text-white"
              >
                <svg
                  role="img"
                  width="20"
                  class="fill-current"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>Facebook</title>
                  <path
                    d="M9.101 23.691v-7.98H6.627v-3.667h2.474v-1.58c0-4.085 1.848-5.978 5.858-5.978.401 0 .955.042 1.468.103a8.68 8.68 0 0 1 1.141.195v3.325a8.623 8.623 0 0 0-.653-.036 26.805 26.805 0 0 0-.733-.009c-.707 0-1.259.096-1.675.309a1.686 1.686 0 0 0-.679.622c-.258.42-.374.995-.374 1.752v1.297h3.919l-.386 2.103-.287 1.564h-3.246v8.245C19.396 23.238 24 18.179 24 12.044c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.628 3.874 10.35 9.101 11.647Z"
                  />
                </svg>
              </a>
  
              <!-- Tiktok -->
              <a
                href="https://tiktok.com/@rizky456737"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-slate-300 hover:border-primary hover:bg-primary hover:text-white"
              >
                <svg
                  role="img"
                  width="20"
                  class="fill-current"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>TikTok</title>
                  <path
                    d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"
                  />
                </svg>
              </a>
            </div>
            <p class="font-medium text-xs text-slate-500 text-center">Dibuat dengan <span class="text-pink-600">❤</span> oleh <a href="https://instagram.com/rizkyarisa_" target="_blank" class="font-bold text-primary">Rizky Aris Adzin</a>, menggunakan <a href="https://tailwindcss.com" target="_blank" class="font-bold text-sky-500">Tailwind CSS</a></p>
          </div>
        </div>
      </footer>
      <!-- Footer End -->
</template>

<script setup>

// import index from '../index.js'
window.onscroll = function () {
    const header = document.querySelector("header");
    const fixedNav = header.offsetTop;
  
    if (window.pageYOffset > fixedNav) {
      header.classList.add("navbar-fixed");
    } else {
      header.classList.remove("navbar-fixed");
    }
  };
  
  const hamburger = document.querySelector("#hamburger");
  const navMenu = document.querySelector("#nav-menu");
  
  // hamburger.addEventListener("click", function () {
  // hamburger.classList.toggle("hamburger-active");
  // navMenu.classList.toggle("hidden");
  // });
  


</script>