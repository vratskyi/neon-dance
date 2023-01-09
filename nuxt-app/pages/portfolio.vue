<template>
  <main
    @mouseenter="showModal()"
    class="relative shadow-top shadow-bottom lg:rounded-2xl lg:mr-[3.333%] 2xl:mr-[10.333%] lg:place-self-end 2xl:place-self-center h-screen lg:max-h-[90%] xl:max-h-[80%] w-full lg:max-w-[80%] xl:max-w-[80%] 2xl:max-w-[70%] 2xl:max-h-[80%] my-auto xl:ml-[12.2222%] 2xl:mx-auto transition-all duration-300 lg:border-4 border-purple-500/30 shadow-2xl shadow-purple-500/50 bg-black/10 lg:bg-black/40 backdrop-blur overflow-y-auto"
  >
    <Head>
      <Title>Portfolio</Title>
    </Head>
    <div id="blurContent" class="transition-all duration-300">
      <div
        class="w-full grid grid-cols-1 lg:grid-cols-2 place-items-start place-content-start p-5 lg:px-10 lg:pt-5 z-10 preserve-3d bg-gradient-to-r from-purple-500/30 to-blue-500/10 rounded-b-2xl shadow-2xl shadow-purple-500/20"
      >
        <div class="grid place-items-start">
          <h1
            class="text-3xl md:text-4xl font-black text-shadow pulseNeon bg-clip-text text-white/50"
          >
            Portfolio
          </h1>
        </div>
        <div class="hidden lg:flex self-center justify-self-end">
          <nuxt-link to="/services">
            <svg
              class="w-8 h-8 text-white"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M14 5l7 7m0 0l-7 7m7-7H3"
              ></path>
            </svg>
          </nuxt-link>
        </div>
      </div>
      <div
        class="grid mt-[1%] 2xl:mt-[3%] place-content-center 2xl:place-content-arround p-5 2xl:p-0"
      >
        <div
          class="grid place-self-start 2xl:mb-10 text-white shadow-top shadow-bottom px-10 py-5 rounded-xl min-w-full"
        >
          <h3 class="text-lg md:text-4xl 2xl:text-3xl font-black">
            Here is my last projects
          </h3>
          <h4 class="text-base md:text-2xl xl:text-xl">
            You can see more of my projects on
            <nuxt-link to="https://www.behance.net/alexvracky" target="_blank"
              ><span
                class="underline underline-offset-4 decoration-sky-500 transition-colors hover:decoration-sky-300 pulseNeon"
                >Behance</span
              ></nuxt-link
            >
          </h4>
        </div>
        <div
          class="grid grid-cols-1 md:grid-cols-2 mb-20 lg:mb-0 mt-10 2xl:mt-0 gap-8 place-items-center"
        >
          <!-- Item 1 -->
          <div class="duration-150 ease-in-out rounded-lg">
            <div class="transition-all duration-150 hover:scale-105">
              <button class="modalTrigger" type="button">
                <nuxt-img
                  src="/assets/img/water-website-min.png"
                  class="max-w-[300px] w-full aspect-video transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
                  alt="h2ovoda.com.ua is a water delivery service based on Astro SSR technology"
                  loading="over-eager"
                />
              </button>
            </div>
          </div>
          <!-- Item 2 -->
          <div class="duration-150 ease-in-out rounded-lg">
            <div class="transition-all duration-150 hover:scale-105">
              <button class="modalTrigger" type="button">
                <nuxt-img
                  src="/assets/img/online-store.png"
                  class="max-w-[300px] w-full aspect-video transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
                  alt="lmd.lviv.ua is a paper gift bags service based on WordPress & WooCommerce technology"
                />
              </button>
            </div>
          </div>
          <!-- Item 3 -->
          <div class="duration-150 ease-in-out rounded-lg">
            <div class="transition-all duration-150 hover:scale-105">
              <button class="modalTrigger" type="button">
                <nuxt-img
                  src="/assets/img/landing-page.png"
                  class="max-w-[300px] w-full aspect-video transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
                  alt="vratsky.com is a personal portfolio site based on Vue 3 and Nuxt 3 technologies"
                />
              </button>
            </div>
          </div>
          <!-- Item 4 -->
          <div class="duration-150 ease-in-out">
            <div class="transition-all duration-150 hover:scale-105">
              <button class="modalTrigger" type="button">
                <nuxt-img
                  src="/assets/img/personal-blog.png"
                  class="max-w-[300px] w-full aspect-video transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
                  alt="blog.vratsky.com is a personal blog site based on Astro SSR technology"
                />
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- MODAL 1 project -->
    <div
      class="grid grid-cols-1 place-items-center place-content-center text-white z-50"
    >
      <div
        id="modal"
        class="hideModal absolute shadow-top shadow-bottom transition-all duration-300 ease-in-out left-0 right-0 top-0 bottom-0 z-50 xl:w-[900px] 2xl:w-[1100px] xl:h-[360px] m-auto backdrop-blur-3xl shadow-top shadow-bottom lg:rounded-t-2xl rounded-b-2xl lg:rounded-b-3xl shadow-2xl shadow-purple-500/50"
      >
        <div class="absolute top-0 right-0 p-4 z-40">
          <button class="closeModal">
            <svg
              class="w-8 h-8 transition-colors duration-300 hover:text-rose-500/70"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M16.3394 9.32245C16.7434 8.94589 16.7657 8.31312 16.3891 7.90911C16.0126 7.50509 15.3798 7.48283 14.9758 7.85938L12.0497 10.5866L9.32245 7.66048C8.94589 7.25647 8.31312 7.23421 7.90911 7.61076C7.50509 7.98731 7.48283 8.62008 7.85938 9.0241L10.5866 11.9502L7.66048 14.6775C7.25647 15.054 7.23421 15.6868 7.61076 16.0908C7.98731 16.4948 8.62008 16.5171 9.0241 16.1405L11.9502 13.4133L14.6775 16.3394C15.054 16.7434 15.6868 16.7657 16.0908 16.3891C16.4948 16.0126 16.5171 15.3798 16.1405 14.9758L13.4133 12.0497L16.3394 9.32245Z"
                fill="currentColor"
              />
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M1 12C1 5.92487 5.92487 1 12 1C18.0751 1 23 5.92487 23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12ZM12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3C16.9706 3 21 7.02944 21 12C21 16.9706 16.9706 21 12 21Z"
                fill="currentColor"
              />
            </svg>
          </button>
        </div>
        <div
          class="grid grid-cols-1 xl:grid-cols-2 lg:mt-[5%] xl:mt-0 lg:max-w-[600px] xl:lg:max-w-full m-auto place-items-center place-content-around lg:p-5"
        >
          <div class="p-5">
            <div>
              <h3 class="sub-title text-white text-shadow font-black">
                Water H2O
              </h3>
              <h4 class="text-base md:text-xl text-white text-shadow">
                Website of a local water delivery service
              </h4>
            </div>

            <div>
              <span
                class="bg-gradient-to-r from-blue-500 to-purple-500 p-2 text-white uppercase rounded-xl text-shadow text-sm font-black mt-4 inline-block"
              >
                Description </span
              ><span
                class="ml-1 lg:ml-4 bg-gradient-to-r from-blue-500 to-purple-500 p-2 text-white uppercase rounded-xl text-shadow text-sm font-black mt-4 inline-block"
              >
                <nuxt-link to="https://h2ovoda.com.ua/" target="_blank"
                  >Watch live project
                  <svg
                    class="w-5 h-5 inline-block"
                    fill="none"
                    stroke="currentColor"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                    ></path></svg></nuxt-link
              ></span>
              <p class="mt-4 text-lg">
                Developed the design in Figma, Done the layout, Made edits to
                the client, Filled it with content, Added functionality, Gave
                the client the finished product, Now I'm maintaining the site.
              </p>
            </div>
          </div>
          <div class="order-first">
            <img
              src="@/assets/img/water-website-min.png"
              class="max-w-[500px] w-full aspect-video"
              loading="lazy"
              alt="h2ovoda.com.ua is a water delivery service based on Astro SSR technology"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- MODAL 2 project -->
    <div
      class="grid grid-cols-1 place-items-center place-content-center text-white z-50"
    >
      <div
        id="modal"
        class="hideModal absolute transition-all duration-300 ease-in-out top-0 bottom-0 left-0 right-0 z-50 xl:w-[900px] 2xl:w-[1100px] xl:h-[340px] 2xl:h-[320px] m-auto backdrop-blur-3xl shadow-top shadow-bottom lg:rounded-t-2xl rounded-b-2xl lg:rounded-b-3xl shadow-2xl shadow-purple-500/50"
      >
        <div class="absolute top-0 right-0 p-4 z-40">
          <button class="closeModal">
            <svg
              class="w-8 h-8 transition-colors duration-300 hover:text-rose-500/70"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M16.3394 9.32245C16.7434 8.94589 16.7657 8.31312 16.3891 7.90911C16.0126 7.50509 15.3798 7.48283 14.9758 7.85938L12.0497 10.5866L9.32245 7.66048C8.94589 7.25647 8.31312 7.23421 7.90911 7.61076C7.50509 7.98731 7.48283 8.62008 7.85938 9.0241L10.5866 11.9502L7.66048 14.6775C7.25647 15.054 7.23421 15.6868 7.61076 16.0908C7.98731 16.4948 8.62008 16.5171 9.0241 16.1405L11.9502 13.4133L14.6775 16.3394C15.054 16.7434 15.6868 16.7657 16.0908 16.3891C16.4948 16.0126 16.5171 15.3798 16.1405 14.9758L13.4133 12.0497L16.3394 9.32245Z"
                fill="currentColor"
              />
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M1 12C1 5.92487 5.92487 1 12 1C18.0751 1 23 5.92487 23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12ZM12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3C16.9706 3 21 7.02944 21 12C21 16.9706 16.9706 21 12 21Z"
                fill="currentColor"
              />
            </svg>
          </button>
        </div>
        <div
          class="grid grid-cols-1 xl:grid-cols-2 lg:mt-[5%] xl:mt-0 lg:max-w-[600px] xl:lg:max-w-full m-auto place-items-center place-content-around lg:p-5"
        >
          <div class="p-5">
            <div>
              <h3 class="sub-title text-white text-shadow font-black">
                Online Store
              </h3>
              <h4 class="text-xl text-white text-shadow">
                Paper gift bags service
              </h4>
            </div>
            <span
              class="bg-gradient-to-r from-blue-500 to-purple-500 p-2 text-white uppercase rounded-xl text-shadow text-sm font-black mt-4 inline-block"
            >
              Description </span
            ><span
              class="ml-1 lg:ml-4 bg-gradient-to-r from-blue-500 to-purple-500 p-2 text-white uppercase rounded-xl text-shadow text-sm font-black mt-4 inline-block"
            >
              <nuxt-link to="http://lmd.lviv.ua/" target="_blank"
                >Watch live project
                <svg
                  class="w-5 h-5 inline-block"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                  ></path></svg></nuxt-link
            ></span>
            <p class="mt-4 text-base">
              This online store is based on WordPress CMS and WooCommerce, I
              redesigned the old site to a modern design and optimized the
              loading time, thanks to a comprehensive approach, the number of
              visitors and sales increased. Now the site is at the top of google
              in Ukraine.
            </p>
          </div>
          <div class="order-first">
            <img
              src="@/assets/img/online-store.png"
              class="max-w-[500px] w-full aspect-video"
              loading="lazy"
              alt="lmd.lviv.ua is a paper gift bags service based on WordPress & WooCommerce technology"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- MODAL 3 project -->
    <div
      class="grid grid-cols-1 place-items-center place-content-center text-white z-50"
    >
      <div
        id="modal"
        class="hideModal absolute transition-all duration-300 ease-in-out left-0 right-0 top-0 bottom-0 z-50 xl:w-[900px] 2xl:w-[1100px] xl:h-[320px] m-auto backdrop-blur-3xl shadow-top shadow-bottom lg:rounded-t-2xl rounded-b-2xl lg:rounded-b-3xl shadow-2xl shadow-purple-500/50"
      >
        <div class="absolute top-0 right-0 p-4 z-40">
          <button class="closeModal">
            <svg
              class="w-8 h-8 transition-colors duration-300 hover:text-rose-500/70"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M16.3394 9.32245C16.7434 8.94589 16.7657 8.31312 16.3891 7.90911C16.0126 7.50509 15.3798 7.48283 14.9758 7.85938L12.0497 10.5866L9.32245 7.66048C8.94589 7.25647 8.31312 7.23421 7.90911 7.61076C7.50509 7.98731 7.48283 8.62008 7.85938 9.0241L10.5866 11.9502L7.66048 14.6775C7.25647 15.054 7.23421 15.6868 7.61076 16.0908C7.98731 16.4948 8.62008 16.5171 9.0241 16.1405L11.9502 13.4133L14.6775 16.3394C15.054 16.7434 15.6868 16.7657 16.0908 16.3891C16.4948 16.0126 16.5171 15.3798 16.1405 14.9758L13.4133 12.0497L16.3394 9.32245Z"
                fill="currentColor"
              />
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M1 12C1 5.92487 5.92487 1 12 1C18.0751 1 23 5.92487 23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12ZM12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3C16.9706 3 21 7.02944 21 12C21 16.9706 16.9706 21 12 21Z"
                fill="currentColor"
              />
            </svg>
          </button>
        </div>
        <div
          class="grid grid-cols-1 xl:grid-cols-2 lg:mt-[5%] xl:mt-0 lg:max-w-[600px] xl:lg:max-w-full m-auto place-items-center place-content-around lg:p-5"
        >
          <div class="p-5">
            <div>
              <h3 class="sub-title text-white text-shadow font-black">
                Landing Page
              </h3>
              <h4 class="text-xl text-white text-shadow">My old website</h4>
            </div>

            <span
              class="bg-gradient-to-r from-blue-500 to-purple-500 p-2 text-white uppercase rounded-xl text-shadow text-sm font-black mt-4 inline-block"
            >
              Description
            </span>
            <p class="mt-4 text-xl">
              One of my old sites that was created using TailwindCSS,
              JavaScript, and UI Kit Flowbite.
            </p>
          </div>
          <div class="order-first">
            <img
              src="@/assets/img/landing-page.png"
              class="max-w-[500px] w-full aspect-video"
              loading="lazy"
              alt="vratsky.com is a personal portfolio site based on Vue 3 and Nuxt 3 technologies"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- MODAL 4 project -->
    <div
      class="grid grid-cols-1 place-items-center place-content-center text-white z-50"
    >
      <div
        id="modal"
        class="hideModal absolute transition-all duration-300 ease-in-out left-0 right-0 top-0 bottom-0 z-50 xl:w-[900px] 2xl:w-[1100px] xl:h-[360px] 2xl:h-[320px] m-auto backdrop-blur-3xl shadow-top shadow-bottom lg:rounded-t-2xl rounded-b-2xl lg:rounded-b-3xl shadow-2xl shadow-purple-500/50"
      >
        <div class="absolute top-0 right-0 p-4 z-40">
          <button class="closeModal">
            <svg
              class="w-8 h-8 transition-colors duration-300 hover:text-rose-500/70"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M16.3394 9.32245C16.7434 8.94589 16.7657 8.31312 16.3891 7.90911C16.0126 7.50509 15.3798 7.48283 14.9758 7.85938L12.0497 10.5866L9.32245 7.66048C8.94589 7.25647 8.31312 7.23421 7.90911 7.61076C7.50509 7.98731 7.48283 8.62008 7.85938 9.0241L10.5866 11.9502L7.66048 14.6775C7.25647 15.054 7.23421 15.6868 7.61076 16.0908C7.98731 16.4948 8.62008 16.5171 9.0241 16.1405L11.9502 13.4133L14.6775 16.3394C15.054 16.7434 15.6868 16.7657 16.0908 16.3891C16.4948 16.0126 16.5171 15.3798 16.1405 14.9758L13.4133 12.0497L16.3394 9.32245Z"
                fill="currentColor"
              />
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M1 12C1 5.92487 5.92487 1 12 1C18.0751 1 23 5.92487 23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12ZM12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3C16.9706 3 21 7.02944 21 12C21 16.9706 16.9706 21 12 21Z"
                fill="currentColor"
              />
            </svg>
          </button>
        </div>
        <div
          class="grid grid-cols-1 xl:grid-cols-2 lg:mt-[5%] xl:mt-0 lg:max-w-[600px] xl:lg:max-w-full m-auto place-items-center place-content-around lg:p-5"
        >
          <div class="p-5">
            <div>
              <h3 class="sub-title text-white text-shadow font-black">Blog</h3>
              <h4 class="text-xl text-white text-shadow">My old blog</h4>
            </div>

            <span
              class="bg-gradient-to-r from-blue-500 to-purple-500 p-2 text-white uppercase rounded-xl text-shadow text-sm font-black mt-4 inline-block"
            >
              Description </span
            ><span
              class="ml-1 lg:ml-4 bg-gradient-to-r from-blue-500 to-purple-500 p-2 text-white uppercase rounded-xl text-shadow text-sm font-black mt-4 inline-block"
            >
              <nuxt-link to="https://blog.vratsky.com/" target="_blank"
                >Watch live project
                <svg
                  class="w-5 h-5 inline-block"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                  ></path></svg></nuxt-link
            ></span>
            <p class="mt-4 text-xl">
              My old blog, which is based on AstroSSR, as well as TailwindCSS
              and Flowbite UI. I created it to practice blog development, soon I
              will make a redesign and rewrite it on Nuxt3 with Content.v2
            </p>
          </div>
          <div class="order-first">
            <img
              src="@/assets/img/personal-blog.png"
              class="max-w-[500px] w-full aspect-video"
              loading="lazy"
              alt="blog.vratsky.com is a personal blog site based on Astro SSR technology"
            />
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  methods: {
    showModal: function () {
      // console.log("Dude im here 😅");
      const triggers = document.getElementsByClassName("modalTrigger");
      const triggerArray = Array.from(triggers).entries();
      const modals = document.querySelectorAll("#modal");
      const closeButtons = document.getElementsByClassName("closeModal");
      const overflow = document.querySelector(".overflow-y-auto");
      const blurContent = document.querySelector("#blurContent");

      for (let [index, trigger] of triggerArray) {
        const toggleModal = () => {
          if (modals[index].classList.contains("hideModal")) {
            modals[index].classList.replace("hideModal", "showModal");
            overflow.classList.remove("overflow-y-auto");
            blurContent.classList.add("blur");
          } else if (modals[index].classList.contains("showModal")) {
            modals[index].classList.replace("showModal", "hideModal");
            overflow.classList.add("overflow-y-auto");
            blurContent.classList.remove("blur");
          } else {
            console.log("Error: can't open modal. ", modals[index]);
          }
        };
        trigger.addEventListener("click", toggleModal);
        closeButtons[index].addEventListener("click", toggleModal);
      }
    },
    mounted() {
      this.showModal();
    },
  },
};
</script>
