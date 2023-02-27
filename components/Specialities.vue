<template>
  <VCard
    class="px-5 lg:px-0 pt-14 lg:pt-12 flex bg-indigo-900 flex-col"
  >
    <!-- <div id="partners" class=" mb-12 lg:mb-20 lg:pt-12">
      <h1 class="font-bold text-3xl text-white text-brand-accent text-center lg:text-4xl">
        Ferramentas
      </h1>
      <div
        class="border border-brand-primary border-l-0 border-r-0 container lg:p-20 mt-6 overflow-hidden p-12 relative"
      >
        <div class="flex animate absolute left-0">
          <div class="flex w-50 justify-around items-center logo">
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>

          </div>
          <div class="flex w-50 justify-around items-center logo">
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>
            <a href="#">LOGO</a>

          </div>
        </div>
      </div>
      <div class="all-partners container mt-12">
        <div v-if="showAll" class="grid grid-cols-3 lg:grid-cols-5 mb-8">
          <div
            v-for="partner in this.partners"
            :key="partner"
            class="text-sm bg-brand-acccentLight border-brand-primary border p-1  text truncate"
            :title="partner"
          >
            {{ partner }}
          </div>
        </div>
        <div
          class="cursor-pointer font-bold text-brand-primary text-center text-lg"
          @click="showPartners"
        >
          <h3>{{ view }}</h3>
        </div>
      </div>
    </div> -->
    <div class="flex flex-col items-center px-10 mt-10">
      <h3
        class="text-2xl text-gray-700 font-bold mb-6 ml-3 text-white text-center"
      >
        FORMAÇÃO
      </h3>

      <ol class="border-l-2 border-blue-300">
        <li>
          <div class="md:flex flex-start">
            <div
              class="bg-blue-300 w-6 h-6 flex items-center justify-center rounded-full -ml-3"
            >
              <svg
                aria-hidden="true"
                focusable="false"
                data-prefix="fas"
                class="text-white w-3 h-3"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 448 512"
              >
                <path
                  fill="currentColor"
                  d="M0 464c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V192H0v272zm64-192c0-8.8 7.2-16 16-16h288c8.8 0 16 7.2 16 16v64c0 8.8-7.2 16-16 16H80c-8.8 0-16-7.2-16-16v-64zM400 64h-48V16c0-8.8-7.2-16-16-16h-32c-8.8 0-16 7.2-16 16v48H160V16c0-8.8-7.2-16-16-16h-32c-8.8 0-16 7.2-16 16v48H48C21.5 64 0 85.5 0 112v48h448v-48c0-26.5-21.5-48-48-48z"
                ></path>
              </svg>
            </div>
            <div
              class="block p-6 rounded-lg shadow-lg bg-gray-100 max-w-md ml-6 mb-10"
            >
              <div class="flex justify-between">
                <a
                  class="font-medium text-blue-600 hover:text-blue-700 focus:text-blue-800 duration-300 transition ease-in-out text-sm mr-2"
                  >Farmácia - UFPR Curitiba</a
                >
                <a
                  class="font-medium text-blue-600 hover:text-blue-700 focus:text-blue-800 duration-300 transition ease-in-out text-sm"
                  >2017</a
                >
              </div>
            </div>
          </div>
        </li>
        <li>
          <div class="md:flex flex-start">
            <div
              class="bg-blue-300 w-6 h-6 flex items-center justify-center rounded-full -ml-3"
            >
              <svg
                aria-hidden="true"
                focusable="false"
                data-prefix="fas"
                class="text-white w-3 h-3"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 448 512"
              >
                <path
                  fill="currentColor"
                  d="M0 464c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V192H0v272zm64-192c0-8.8 7.2-16 16-16h288c8.8 0 16 7.2 16 16v64c0 8.8-7.2 16-16 16H80c-8.8 0-16-7.2-16-16v-64zM400 64h-48V16c0-8.8-7.2-16-16-16h-32c-8.8 0-16 7.2-16 16v48H160V16c0-8.8-7.2-16-16-16h-32c-8.8 0-16 7.2-16 16v48H48C21.5 64 0 85.5 0 112v48h448v-48c0-26.5-21.5-48-48-48z"
                ></path>
              </svg>
            </div>
            <div
              class="block p-6 rounded-lg shadow-lg bg-gray-100 max-w-md ml-6 mb-10"
            >
              <div class="flex justify-between">
                <a
                  class="font-medium text-blue-600 hover:text-blue-700 focus:text-blue-800 duration-300 transition ease-in-out text-sm mr-2"
                  >Especialização em acupuntura - ABATE</a
                >
                <a
                  class="font-medium text-blue-600 hover:text-blue-700 focus:text-blue-800 duration-300 transition ease-in-out text-sm"
                  >2018</a
                >
              </div>
            </div>
          </div>
        </li>
        <li>
          <div class="md:flex flex-start">
            <div
              class="bg-blue-300 w-6 h-6 flex items-center justify-center rounded-full -ml-3"
            >
              <svg
                aria-hidden="true"
                focusable="false"
                data-prefix="fas"
                class="text-white w-3 h-3"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 448 512"
              >
                <path
                  fill="currentColor"
                  d="M0 464c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V192H0v272zm64-192c0-8.8 7.2-16 16-16h288c8.8 0 16 7.2 16 16v64c0 8.8-7.2 16-16 16H80c-8.8 0-16-7.2-16-16v-64zM400 64h-48V16c0-8.8-7.2-16-16-16h-32c-8.8 0-16 7.2-16 16v48H160V16c0-8.8-7.2-16-16-16h-32c-8.8 0-16 7.2-16 16v48H48C21.5 64 0 85.5 0 112v48h448v-48c0-26.5-21.5-48-48-48z"
                ></path>
              </svg>
            </div>
            <div
              class="block p-6 rounded-lg shadow-lg bg-gray-100 max-w-md ml-6 mb-10"
            >
              <div class="flex justify-between">
                <a
                  class="font-medium text-blue-600 hover:text-blue-700 focus:text-blue-800 duration-300 transition ease-in-out text-sm mr-2"
                  >Especialização em Quiropraxia - ABATE</a
                >
                <a
                  class="font-medium text-blue-600 hover:text-blue-700 focus:text-blue-800 duration-300 transition ease-in-out text-sm"
                  >2022</a
                >
              </div>
            </div>
          </div>
        </li>
        <li>
          <div class="md:flex flex-start">
            <div
              class="bg-blue-300 w-6 h-6 flex items-center justify-center rounded-full -ml-3"
            >
              <svg
                aria-hidden="true"
                focusable="false"
                data-prefix="fas"
                class="text-white w-3 h-3"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 448 512"
              >
                <path
                  fill="currentColor"
                  d="M0 464c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V192H0v272zm64-192c0-8.8 7.2-16 16-16h288c8.8 0 16 7.2 16 16v64c0 8.8-7.2 16-16 16H80c-8.8 0-16-7.2-16-16v-64zM400 64h-48V16c0-8.8-7.2-16-16-16h-32c-8.8 0-16 7.2-16 16v48H160V16c0-8.8-7.2-16-16-16h-32c-8.8 0-16 7.2-16 16v48H48C21.5 64 0 85.5 0 112v48h448v-48c0-26.5-21.5-48-48-48z"
                ></path>
              </svg>
            </div>
            <div
              class="block p-6 rounded-lg shadow-lg bg-gray-100 max-w-md ml-6 mb-10"
            >
              <div class="flex justify-between">
                <a
                  class="font-medium text-blue-600 hover:text-blue-700 focus:text-blue-800 duration-300 transition ease-in-out text-sm mr-2"
                  >Especialização em Massoterapia - ABATE</a
                >
                <a
                  class="font-medium text-blue-600 hover:text-blue-700 focus:text-blue-800 duration-300 transition ease-in-out text-sm"
                  >2023</a
                >
              </div>
            </div>
          </div>
        </li>
      </ol>
    </div>
    <body
      class="antialiased bg-gray-200 text-gray-900 font-sans p-6 rounded-md"
    >
      <div class="container mx-auto">
        <div class="flex flex-wrap -mx-4">
          <div class="w-full sm:w-1/2 md:w-1/2 xl:w-1/4 p-4">
            <a
              href=""
              class="c-card block bg-white shadow-md hover:shadow-xl rounded-lg overflow-hidden"
            >
              <div class="relative pb-48 overflow-hidden">
                <img
                  class="absolute inset-0 h-full w-full object-cover"
                  src="../assets/img/acupuntura.jpg"
                  alt=""
                />
              </div>
              <div class="p-4">
                <h2 class="mt-2 mb-2 font-bold">Acupuntura</h2>
                <p class="text-sm">
                  é um recurso terapêutico que utiliza agulhas específicas
                  visando estimular determinados pontos pelo corpo, para
                  promoção, manutenção e recuperação da saúde. Sua história
                  remete há mais de 2 mil anos e integra as práticas da Medicina
                  Tradicional Chinesa, conhecida como MTC..
                </p>
              </div>
            </a>
          </div>
          <div class="w-full sm:w-1/2 md:w-1/2 xl:w-1/4 p-4">
            <a
              href=""
              class="c-card block bg-white shadow-md hover:shadow-xl rounded-lg overflow-hidden"
            >
              <div class="relative pb-48 overflow-hidden">
                <img
                  class="absolute inset-0 h-full w-full object-cover"
                  src="../assets/img/moxaterapia.jpeg"
                  alt=""
                />
              </div>
              <div class="p-4">
                <h2 class="mt-2 mb-2 font-bold">Quiropraxia</h2>
                <p class="text-sm">
                  é uma forma pseudocientífica de medicina alternativa baseada
                  no diagnóstico e tratamento de condições do sistema
                  músculo-esquelético, principalmente da coluna vertebral. Os
                  proponentes alegam que essas condições afetam o estado geral
                  de saúde através do sistema nervoso.
                </p>
              </div>
            </a>
          </div>
          <div class="w-full sm:w-1/2 md:w-1/2 xl:w-1/4 p-4">
            <a
              href=""
              class="c-card block bg-white shadow-md hover:shadow-xl rounded-lg overflow-hidden"
            >
              <div class="relative pb-48 overflow-hidden">
                <img
                  class="absolute inset-0 h-full w-full object-cover"
                  src="../assets/img/moxaterapia.jpeg"
                  alt=""
                />
              </div>
              <div class="p-4 mb-10">
                <h2 class="mt-2 mb-2 font-bold">Moxaterapia</h2>
                <p class="text-sm">
                  Moxabustão é uma espécie de acupuntura térmica, feita pela
                  combustão da erva Artemisia sinensis e Artemisia vulgaris. É
                  uma técnica terapêutica da Medicina Tradicional Chinesa.
                </p>
              </div>
            </a>
          </div>
          <div class="w-full sm:w-1/2 md:w-1/2 xl:w-1/4 p-4">
            <a
              href=""
              class="c-card block bg-white shadow-md hover:shadow-xl rounded-lg overflow-hidden"
            >
              <div class="relative pb-48 overflow-hidden">
                <img
                  class="absolute inset-0 h-full w-full object-cover"
                  src="../assets/img/massoterapia.jpg"
                  alt=""
                />
              </div>
              <div class="p-4">
                <h2 class="mt-2 mb-2 font-bold">Massoterapia</h2>
                <p class="text-sm">
                  Massagem também conhecida como massoterapia, é uma prática que
                  consiste na aplicação da força ou vibração sobre os tecidos
                  moles, a fim de estimular a circulação sanguínea, a
                  mobilidade, a elasticidade ou alívio de determinadas dores
                  corporais ou traumas físicosa.
                </p>
              </div>
            </a>
          </div>
          <div class="w-full sm:w-1/2 md:w-1/2 xl:w-1/4 p-4">
            <a
              href=""
              class="c-card block bg-white shadow-md hover:shadow-xl rounded-lg overflow-hidden"
            >
              <div class="relative pb-48 overflow-hidden">
                <img
                  class="absolute inset-0 h-full w-full object-cover"
                  src="../assets/img/ventosaterapia.jpg"
                  alt=""
                />
              </div>
              <div class="p-4 mb-10">
                <h2 class="mt-2 mb-2 font-bold">Ventosaterapia</h2>
                <p class="text-sm">
                  Ventosaterapia é uma forma de medicina alternativa no qual é
                  feita uma sucção na pele através de ventosas. Sua prática
                  ocorre principalmente na Ásia, mas também na Europa Oriental,
                  Oriente Médio e América Latina.
                </p>
              </div>
            </a>
          </div>
          <div class="w-full sm:w-1/2 md:w-1/2 xl:w-1/4 p-4">
            <a
              href=""
              class="c-card block bg-white shadow-md hover:shadow-xl rounded-lg overflow-hidden"
            >
              <div class="relative pb-48 overflow-hidden">
                <img
                  class="absolute inset-0 h-full w-full object-cover"
                  src="../assets/img/acupuntura.jpg"
                  alt=""
                />
              </div>
              <div class="p-4">
                <h2 class="mt-2 mb-2 font-bold">Acupuntura</h2>
                <p class="text-sm">
                  é um recurso terapêutico que utiliza agulhas específicas
                  visando estimular determinados pontos pelo corpo, para
                  promoção, manutenção e recuperação da saúde. Sua história
                  remete há mais de 2 mil anos e integra as práticas da Medicina
                  Tradicional Chinesa, conhecida como MTC..
                </p>
              </div>
            </a>
          </div>
          <div class="w-full sm:w-1/2 md:w-1/2 xl:w-1/4 p-4">
            <a
              href=""
              class="c-card block bg-white shadow-md hover:shadow-xl rounded-lg overflow-hidden"
            >
              <div class="relative pb-48 overflow-hidden">
                <img
                  class="absolute inset-0 h-full w-full object-cover"
                  src="../assets/img/moxaterapia.jpeg"
                  alt=""
                />
              </div>
              <div class="p-4">
                <h2 class="mt-2 mb-2 font-bold">Quiropraxia</h2>
                <p class="text-sm">
                  é uma forma pseudocientífica de medicina alternativa baseada
                  no diagnóstico e tratamento de condições do sistema
                  músculo-esquelético, principalmente da coluna vertebral. Os
                  proponentes alegam que essas condições afetam o estado geral
                  de saúde através do sistema nervoso.
                </p>
              </div>
            </a>
          </div>
          <div class="w-full sm:w-1/2 md:w-1/2 xl:w-1/4 p-4">
            <a
              href=""
              class="c-card block bg-white shadow-md hover:shadow-xl rounded-lg overflow-hidden"
            >
              <div class="relative pb-48 overflow-hidden">
                <img
                  class="absolute inset-0 h-full w-full object-cover"
                  src="../assets/img/massoterapia.jpg"
                  alt=""
                />
              </div>
              <div class="p-4">
                <h2 class="mt-2 mb-2 font-bold">Massoterapia</h2>
                <p class="text-sm">
                  Massagem também conhecida como massoterapia, é uma prática que
                  consiste na aplicação da força ou vibração sobre os tecidos
                  moles, a fim de estimular a circulação sanguínea, a
                  mobilidade, a elasticidade ou alívio de determinadas dores
                  corporais ou traumas físicosa.
                </p>
              </div>
            </a>
          </div>
        </div>
      </div>
    </body>
    <!-- commerce slide cards -->
    <!-- <div style="background-color:#fff8f4" class="h-full">
    <div class="container mx-auto  lg:px-20" >
        <div class='grid grid-cols-3 h-full pb-40'>
            <div class="border-r border-gray-300 mx-3 lg:pl-20">
                <div class=" py-10 pb-3 mt-72 h-4/6 relative bg-purple-100 group hover:bg-purple-200 cursor-pointer transition ease-out duration-300"> 
                    <div>
                        <div class="w-4 h-1/5 bg-red-50	absolute right-0 -top-48 bg-purple-100 group-hover:bg-purple-50"></div>
                        <img src="https://i.ibb.co/FzkhpcD/pngegg.png" alt="https://www.pngegg.com/en/png-nllal/download">
                    </div>
                    <div class="px-7 mt-20">
                        <h1 class="text-3xl font-bold group-hover:text-purple-300 transition ease-out duration-300">01.</h1>
                        <h2  class="text-1xl mt-4 font-bold">Roof light lamp</h2>
                        <p class="mt-2 opacity-60 group-hover:opacity-70 ">Diverse collection of roof lights of quality</p>
                    </div>
                </div>
            </div>
            <div class="border-r border-gray-300 mx-3 lg:pl-20">
                <div class=" py-10  pb-3 mt-32 h-4/6 relative bg-indigo-100 group hover:bg-indigo-200 cursor-pointer transition ease-out duration-300"> 
                    <div>
                        <div class="w-4 h-1/5 bg-red-50	absolute right-0 -top-48 bg-indigo-100  group-hover:bg-indigo-50"></div>
                        <img src="https://i.ibb.co/JB4GWMJ/pngegg-1.png" alt="https://www.pngegg.com/en/png-zquqj/download">
                    </div>
                   <div class="px-7 mt-20">
                        <h1 class="text-3xl font-bold group-hover:text-indigo-300 transition ease-out duration-300">02.</h1>
                        <h2  class="text-1xl mt-4 font-bold">Lounge Chair</h2>
                        <p class="mt-2 opacity-60 group-hover:opacity-70 ">Comfortable collection of perfect lounge chairs</p>
                    </div>
                </div>
            </div>
            <div class="border-r border-gray-300 mx-3 lg:pl-20">
                <div class=" py-10 pb-3 mt-5 h-4/6 relative bg-red-100 group hover:bg-red-200 cursor-pointer transition ease-out duration-300"> 
                     <div>
                        <div class="w-4 h-1/5 bg-red-50	absolute right-0 -bottom-44 bg-red-100 group-hover:bg-red-50"></div>
                        <img src="https://i.ibb.co/MgnH44p/pngegg-2.png" alt="https://www.pngegg.com/en/png-epwii/download">
                    </div>
                    <div class="px-7 mt-5">
                        <h1 class="text-3xl font-bold group-hover:text-red-300 transition ease-out duration-300">03.</h1>
                        <h2  class="text-1xl mt-4 font-bold">Scandinavia Couch</h2>
                        <p class="mt-2 opacity-60 group-hover:opacity-70 ">Best selection of scandinavia couch for your home</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div> -->
  </VCard>
</template>

<script>
export default {
  data() {
    return {
      view: "View All",
      showAll: false,
    };
  },
  methods: {
    showPartners() {
      if (!this.showAll) {
        this.showAll = true;
        this.view = "Show Less";
      } else {
        this.showAll = false;
        this.view = "View All";
      }
    },
  },
};
</script>

<style>
@keyframes marquee {
  0% {
    left: 0;
  }
  100% {
    left: -900%;
  }
}
.animate {
  width: 100%;
  animation: marquee 5s linear infinite;
  top: 50%;
  transform: translate(0, -50%);
}
.logo a {
  width: 80px;
  -webkit-transition: all 0.5s cubic-bezier(0.19, 1, 0.22, 1);
}
@screen lg {
  @keyframes marquee {
    0% {
      left: -0%;
    }
    100% {
      left: -70%;
    }
  }
  .animate {
    width: 150%;
    animation: marquee 5s linear infinite;
    top: 50%;
    transform: translate(0, -50%);
  }
  .logo a {
    width: 100px;
    -webkit-transition: all 0.5s cubic-bezier(0.19, 1, 0.22, 1);
  }
}
.animate:hover {
  animation-play-state: paused;
}
.logo a:hover {
  transform: scale(1.3);
}

.c-card {
  img {
    transition: transform 0.3s ease-in-out;
  }

  &:hover {
    img {
      transform: scale(1.05);
    }
  }
}
</style>
