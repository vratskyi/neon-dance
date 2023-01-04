<template>
  <main
    @mouseenter="
      {
        faq(), hoverItem();
      }
    "
    @mouseleave="
      {
        faq(), hoverItem();
      }
    "
    class="relative shadow-top shadow-bottom lg:rounded-2xl lg:mr-[3.333%] 2xl:mr-[10.333%] lg:place-self-end 2xl:place-self-center h-screen lg:max-h-[90%] xl:max-h-[80%] w-full lg:max-w-[80%] xl:max-w-[80%] 2xl:max-w-[70%] 2xl:max-h-[80%] my-auto xl:ml-[12.2222%] 2xl:mx-auto transition-all duration-300 lg:border-4 border-purple-500/30 shadow-2xl shadow-purple-500/50 bg-black/10 lg:bg-black/30 backdrop-blur overflow-y-auto"
  >
    <Head>
      <Title>Contact</Title>
    </Head>
    <div
      class="w-full grid place-items-start place-content-start p-5 lg:px-10 lg:pt-5 preserve-3d bg-gradient-to-r from-purple-500/30 to-blue-500/10 rounded-b-2xl shadow-2xl shadow-purple-500/20"
    >
      <div class="grid place-items-start">
        <h1
          class="text-3xl md:text-4xl font-black text-shadow pulseNeon bg-clip-text text-white/50"
        >
          Contact
        </h1>
      </div>
    </div>
    <div>
      <div class="p-5 mx-5 mt-5">
        <ul
          class="grid place-items-center place-content-center grid-cols-1 xl:grid-cols-3 2xl:grid-cols-5 gap-3 xl:gap-5 my-5 text-white/80 cursor-default"
        >
          <li
            id="hoverItem"
            class="bg-gradient-to-r flex justify-center items-center from-blue-500/30 to-purple-500/10 p-4 min-w-full h-full rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <span class="text-white font-medium mr-2">Country:</span> Ukraine
            <img
              class="inline-block w-6 mr-2 pulseNeon"
              src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAABmJLR0QA/wD/AP+gvaeTAAADjUlEQVRoge2ZT2wUVRzHv9+306rQkgCSiIU0IDBNOO6C4diGi57w4J9YTTyYNE0L4U5MMDHehW5lY8KpJFA8aKIcG25E2r27DZoGazVK98COJS2d+XqAGJw/nXn7Z2jCfo6/93s7n9++eTPz3gO6dHmxYVt+ZVaFwXrjpAkwLLBogCEB+wH0Pc3wBKwAqBGqCppb+mvXXVxk0OqlWyrgjfLaQTGYAPSRgAHLKy8r4Izjm/K9czuWm3VoqoAjlxr7fAdfAPgEQG+zF3/KBoGrTkGfLY7temDb2bqAw9Peh4IuA9hj2zeFVRGTS+P91206ZS6gWFFP3femAXxqrWYBhcpup+9sdYyPM+VnSXq9oh0v+41vBb7Vml42JN3acPrfXRnjWlquSUsoVtSTpzwAkHz7Jd/7/visUudXagF135vOU/4ZTj964H2VlrTlLXT4a29U0kz7nOyR8MHSRP+NpPbEAgamHu7tNfwZwKsdMctOvacgN+kRm3gL9Rp+iecvDwB7Hgf8PKkxdgSOXFo74Dv+L2j9JdUuNlhwjv469sr9cEPsCAROMIntIw8AvcGmPx7XEC3gooyo0Y4rWWKojzGrQiQeDgy+1ngTwoF8tLIjYODQ6sNiOB4pwAQYzkfJHoIj4VikAIqlfHTsEZg+AgFxLB+dpnDDgegIPFlJbU8UdYt7jPbFxLYL/eGAEw7cG4nMk21F+DkaNwJeHiJN0ggHogUQf+Si0hwRt+gkDrCYj4s9BGvhWKQAQQv56NgjIOIWfROrMJePjj2GirhFPqclmKB2YgnAwVyssnPfuPOHSPxvNy86B4gAwrX8vDJCXAvLAwnrAeOYMoCNjktlZ93AKcc1xBbAoz8tA7raWScLyG/o3vk9rilxTWz8ngsArPcqO8CqgZ+4Jk4sgMfv1EWd7YxTdgSO060m/pFbbmw57sJ1gJX2a2VEKDtDd29ulZK6M2fcwQlC37XPKhuUfjR/7jyflpdaAHnTp6dRgrfao5YOiR/4j97j8O3NtNzUAgCApeoaPf8MoCut66UglLmy8x2Wqqk700ATBxybtRPvU5hC+3ft/hY4kXbPh8k0As/iuPM3jDgEYBrAum3/GNZBThnfGbKVB1o85FPt1EAQbE6CGIX9t9NvIGYMnHLSSyoLbTlmlWCwWCoF4AjFoiAXT04t/ztmBbRMmEUBC4aaw7H5aty3TZcuXez4F3L2Eh2go8QYAAAAAElFTkSuQmCC"
            />
          </li>
          <li
            id="hoverItem"
            class="bg-gradient-to-r flex justify-center items-center from-blue-500/30 to-purple-500/10 px-2 py-5 min-w-full h-full rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <span class="text-white font-medium mr-2">Full Name:</span> Oleksii
            Vratskyi
          </li>
          <li
            id="hoverItem"
            class="bg-gradient-to-r flex justify-center items-center from-blue-500/30 to-purple-500/10 px-2 py-5 min-w-full h-full rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <span class="text-white font-medium mr-2">Role:</span> Front-end,
            UI/UX
          </li>
          <li
            id="hoverItem"
            class="bg-gradient-to-r flex justify-center gap-x-3 items-center from-blue-500/30 to-purple-500/10 px-2 py-5 min-w-full h-full rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <span class="text-white font-medium mr-2">Socials: </span>
            <a href="https://t.me/vratsky1" target="_blank">
              <svg
                class="inline-block w-6 h-6 rotate-[18deg] mb-1"
                fill="#0ea5e9"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.429A1 1 0 009 15.571V11a1 1 0 112 0v4.571a1 1 0 00.725.962l5 1.428a1 1 0 001.17-1.408l-7-14z"
                ></path>
              </svg>
            </a>
            <a href="https://www.behance.net/alexvracky" target="_blank">
              <svg
                class="w-8 inline-block"
                fill="white"
                xmlns="http://www.w3.org/2000/svg"
                x="0px"
                y="0px"
                width="50"
                height="50"
                viewBox="0 0 50 50"
              >
                <path
                  d="M 9 4 C 6.24 4 4 6.24 4 9 L 4 41 C 4 43.76 6.24 46 9 46 L 41 46 C 43.76 46 46 43.76 46 41 L 46 9 C 46 6.24 43.76 4 41 4 L 9 4 z M 12 18 L 18.730469 18 C 19.460469 18 23.410156 17.950312 23.410156 21.570312 C 23.410156 23.490313 22.099766 24.139688 21.509766 24.429688 C 22.389766 24.709688 24 25.52 24 28 C 24 31.83 19.609531 32 19.019531 32 L 12 32 L 12 18 z M 29 18 L 36 18 L 36 20 L 29 20 L 29 18 z M 15 20.429688 L 15 23.710938 L 18.220703 23.710938 C 18.660703 23.710938 20.119141 23.47 20.119141 22 C 20.119141 20.53 18.219687 20.429688 17.929688 20.429688 L 15 20.429688 z M 32.730469 21 C 36.630469 21 37.689609 24.039766 37.849609 24.759766 C 37.999609 25.489766 38 26.13 38 27 L 30.099609 27 C 30.099609 27.87 30.560625 29.830078 32.890625 29.830078 C 33.510625 29.830078 33.969453 29.680625 34.439453 29.390625 C 34.899453 29.100625 35.060938 28.819297 35.210938 28.529297 L 37.839844 28.529297 C 37.379844 29.679297 36.760078 30.550859 35.830078 31.130859 C 34.900078 31.710859 33.820078 32 32.580078 32 C 31.800078 32 31.03 31.850547 30.25 31.560547 C 29.63 31.270547 29.010781 30.840156 28.550781 30.410156 C 28.090781 29.970156 27.780703 29.389922 27.470703 28.669922 C 27.160703 28.089922 27 27.22 27 26.5 C 27 25.78 27.290469 21 32.730469 21 z M 32.730469 23.029297 C 30.470469 23.029297 30.099609 25.199844 30.099609 25.339844 L 35.060547 25.339844 C 34.900547 24.619844 34.250469 23.029297 32.730469 23.029297 z M 15 25.710938 L 15 29.570312 L 18.351562 29.570312 C 18.640563 29.570312 20.679688 29.480937 20.679688 27.710938 C 20.679687 25.950937 19.077562 25.710938 18.351562 25.710938 L 15 25.710938 z"
                ></path>
              </svg>
            </a>
          </li>
          <a href="tel:+380736003200" class="text-base min-w-full h-full">
            <li
              id="hoverItem"
              class="bg-gradient-to-r flex justify-center items-center from-blue-500/30 to-purple-500/10 px-2 py-5 min-w-full h-full rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
            >
              +38 (073) 600-32-00
            </li>
          </a>
        </ul>
      </div>
    </div>
    <div
      class="grid lg:grid-cols-1 2xl:grid-cols-2 place-content-center p-5 lg:p-10 gap-8 lg:mx-auto lg:max-w-3xl lg:w-full 2xl:mx-0 2xl:max-w-none 2xl:w-auto"
    >
      <div
        class="grid place-content-center place-self-start bg-gradient-to-r from-purple-500/30 to-blue-500/10 rounded-xl p-5"
      >
        <div class="mb-10">
          <h3
            class="text-2xl md:text-3xl lg:text-4xl 2xl:text-4xl text-shadow text-white text-shadow font-black"
          >
            Ready to go?
          </h3>
          <p class="mt-4 text-lg text-white/80">
            You can describe in short what project you want, also you can attach
            a link to an example of a project that you want, I will study your
            wishes and contact to clarify the details and further cooperation,
            as well we can meet in Kyiv or communicate by video in any social
            network <span class="pulseNeon text-lg">😇</span>
          </p>
        </div>
        <div>
          <form
            method="POST"
            action="order_water.php"
            enctype="multipart/form-data"
            class="grid"
          >
            <div class="grid lg:grid-cols-2 gap-x-4">
              <div class="lg:mb-6">
                <label
                  for="name"
                  class="block my-2 text-sm font-medium text-white/80"
                  >Your Name</label
                >
                <input
                  type="text"
                  name="name"
                  id="name"
                  class="w-full shadow-top shadow-bottom bg-transparent placeholder-white/80 text-sm text-white/80 rounded-lg focus:ring-purple-500 block p-2.5"
                  placeholder="Jon Smith"
                  required
                />
              </div>
              <div class="mb-6">
                <label
                  for="email"
                  class="block my-2 text-sm font-medium text-white/80"
                  >Your email</label
                >
                <input
                  type="email"
                  name="email"
                  id="email"
                  class="w-full shadow-top shadow-bottom bg-transparent placeholder-white/80 text-white/80 text-sm rounded-lg focus:ring-purple-500 block p-2.5"
                  placeholder="name@vratsky.com"
                  required
                />
              </div>
            </div>

            <h3 class="my-2 text-sm text-white/80">Who do you represent?</h3>
            <div class="grid lg:grid-cols-2 gap-y-4 lg:gap-y-0 gap-x-4">
              <div
                id="hoverItem"
                class="flex items-center px-5 bg-gradient-to-r from-purple-500/30 to-blue-500/10 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500 rounded-lg"
              >
                <input
                  id="bordered-radio-1"
                  type="radio"
                  value="Myself"
                  name="bordered-radio"
                  class="w-1 h-1 text-purple-500 shadow-top shadow-bottom focus:ring-purple-500 focus:ring"
                />
                <label
                  for="bordered-radio-1"
                  class="py-4 ml-2 w-full text-sm font-medium text-white/80 cursor-pointer peer-checked:shadow-xl peer-checked:shadow-indigo-500 peer-checked:text-white"
                  >Myself</label
                >
              </div>
              <div
                id="hoverItem"
                class="flex items-center px-5 bg-gradient-to-r from-purple-500/30 to-blue-500/10 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500 rounded-lg"
              >
                <input
                  id="bordered-radio-2"
                  type="radio"
                  value="Company"
                  name="bordered-radio"
                  class="w-1 h-1 text-purple-500 shadow-top shadow-bottom focus:ring-purple-500 focus:ring"
                />
                <label
                  for="bordered-radio-2"
                  class="py-4 ml-2 w-full text-sm font-medium text-white/80 cursor-pointer peer-checked:shadow-xl peer-checked:shadow-indigo-500 peer-checked:text-white"
                  >Company</label
                >
              </div>
            </div>

            <h3 class="mt-6 mb-2 text-sm text-white/80">
              Your budget for project:
            </h3>
            <ul class="grid w-full lg:grid-cols-3 gap-y-4 lg:gap-y-0">
              <li
                id="hoverItem"
                class="transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500 rounded-lg"
              >
                <input
                  type="checkbox"
                  name="small"
                  id="react-option"
                  value="Small-$300"
                  class="hidden peer"
                  required=""
                />
                <label
                  for="react-option"
                  class="inline-grid px-3 py-5 w-full h-full lg:min-h-[110px] text-white/80 bg-gradient-to-r from-purple-500/30 to-blue-500/10 rounded-lg cursor-pointer peer-checked:shadow-xl peer-checked:shadow-indigo-500 peer-checked:text-white"
                >
                  <div class="block text-center">
                    <span class="pulseNeon text-xl">🔥</span>
                    <div class="w-full text-sm mt-3 font-semibold">
                      Small - $300+
                    </div>
                  </div>
                </label>
              </li>
              <li
                id="hoverItem"
                class="lg:mx-2 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500 rounded-lg"
              >
                <input
                  type="checkbox"
                  name="medium"
                  id="flowbite-option"
                  value="Medium-$1000"
                  class="hidden peer"
                />
                <label
                  for="flowbite-option"
                  class="inline-grid px-3 py-5 w-full h-full lg:min-h-[110px] text-white/80 bg-gradient-to-r from-purple-500/30 to-blue-500/10 rounded-lg cursor-pointer peer-checked:shadow-xl peer-checked:shadow-indigo-500 peer-checked:text-white"
                >
                  <div class="block text-center">
                    <span class="pulseNeon text-2xl">🔥</span>
                    <div class="w-full text-sm mt-3 font-semibold">
                      Medium - $1000+
                    </div>
                  </div>
                </label>
              </li>
              <li
                id="hoverItem"
                class="transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500 rounded-lg"
              >
                <input
                  type="checkbox"
                  name="big"
                  id="angular-option"
                  value="Big-$3000"
                  class="hidden peer"
                />
                <label
                  for="angular-option"
                  class="inline-grid px-3 py-5 w-full h-full lg:min-h-[110px] text-white/80 bg-gradient-to-r from-purple-500/30 to-blue-500/10 rounded-lg cursor-pointer peer-checked:shadow-xl peer-checked:shadow-indigo-500 peer-checked:text-white"
                >
                  <div class="block text-center">
                    <span class="pulseNeon text-3xl">🔥</span>
                    <div class="w-full text-sm mt-3 lg:mt-2 font-semibold">
                      Big - $3000+
                    </div>
                  </div>
                </label>
              </li>
            </ul>

            <label
              for="message"
              class="block lg:mt-6 mb-2 text-sm font-medium text-white/80"
              >Your message</label
            >
            <textarea
              id="message"
              name="message"
              rows="4"
              class="block p-2.5 w-full text-sm text-white/80 shadow-top shadow-bottom rounded-lg border focus:ring-purple-500 focus:border-purple-500"
              placeholder="Your message..."
            ></textarea>

            <button
              id="hoverItem"
              type="submit"
              class="text-white text-center py-3 px-5 mt-5 w-[150px] transition-all duration-150 rounded-lg text-sm bg-gradient-to-r from-purple-500/30 to-blue-500/10 hover:shadow-2xl hover:shadow-indigo-500"
            >
              Send massage
            </button>
          </form>
        </div>
      </div>
      <div
        class="grid place-self-start min-w-full shadow-top shadow-bottom lg:p-5 mb-10 lg:mb-0 rounded-xl"
      >
        <div class="grid place-content-center place-items-center w-full h-full">
          <section class="p-5">
            <div class="faqItem mb-5">
              <button
                id="hoverItem"
                type="button"
                class="faqButton w-full bg-gradient-to-r from-purple-500/30 to-blue-500/10 transition-all duration-150 p-5 rounded-xl hover:shadow-2xl hover:shadow-indigo-500"
              >
                <h4 class="text-base font-medium text-white/80 text-left">
                  After the project is completed, do you maintain the website?
                </h4>
              </button>
              <div
                id="faqContent"
                class="block transition-all duration-150 w-full shadow-top shadow-bottom rounded-xl p-5 mb-5"
              >
                <p class="text-base text-white/80 text-left">
                  Yes, of course, there are two options for website maintenance,
                  edits on a piece fee, or maintenance by subscription, from $50
                  per month.
                </p>
              </div>
            </div>

            <div class="faqItem mb-5">
              <button
                id="hoverItem"
                type="button"
                class="faqButton w-full bg-gradient-to-r from-purple-500/30 to-blue-500/10 transition-all duration-150 p-5 rounded-xl hover:shadow-2xl hover:shadow-indigo-500"
              >
                <h4 class="text-base font-medium text-white/80 text-left">
                  After the project is completed, do you promotion the website?
                </h4>
              </button>
              <div
                id="faqContent"
                class="hidden transition-all duration-150 w-full shadow-top shadow-bottom rounded-xl p-5 mb-5"
              >
                <p class="text-base text-white/80 text-left">
                  Of course, we have experience in promoting large projects,
                  both offline stores and online solutions, we know how to find
                  the highlight, as well as adapt your project to the specific
                  market and features of the niche of your business.
                </p>
              </div>
            </div>

            <div class="faqItem mb-5">
              <button
                id="hoverItem"
                type="button"
                class="faqButton w-full bg-gradient-to-r from-purple-500/30 to-blue-500/10 transition-all duration-150 p-5 rounded-xl hover:shadow-2xl hover:shadow-indigo-500"
              >
                <h4 class="text-base font-medium text-white/80 text-left">
                  Can you draw a design for my project?
                </h4>
              </button>
              <div
                id="faqContent"
                class="hidden transition-all duration-150 w-full shadow-top shadow-bottom rounded-xl p-5 mb-5"
              >
                <p class="text-base text-white/80 text-left">
                  Yes I can, there are options to render a partial design (MVP -
                  minimum viable product) & MMP, or a full design project, which
                  at your request may include UI / UX reserch. I believe that
                  design is one of the most important components of a website.
                </p>
              </div>
            </div>

            <div class="faqItem mb-5">
              <button
                id="hoverItem"
                type="button"
                class="faqButton w-full bg-gradient-to-r from-purple-500/30 to-blue-500/10 transition-all duration-150 p-5 rounded-xl hover:shadow-2xl hover:shadow-indigo-500"
              >
                <h4 class="text-base font-medium text-white/80 text-left">
                  I need a website, but I don't know what kind
                </h4>
              </button>
              <div
                id="faqContent"
                class="hidden transition-all duration-150 w-full shadow-top shadow-bottom rounded-xl p-5"
              >
                <p class="text-base text-white/80 text-left">
                  To solve your problem, we will need to hold a consultation
                  with you to understand what you do, what your product does,
                  who it is for, based on these and other data I will be able to
                  advise you what website you need and where we start
                  cooperating.
                </p>
              </div>
            </div>
          </section>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  methods: {
    hoverItem: function () {
      const triggers = document.querySelectorAll("#hoverItem");
      const triggerArray = Array.from(triggers).entries();

      for (let [index, trigger] of triggerArray) {
        const addHover = () => {
          triggers[index].classList.add("pulseNeon");
        };
        const removeHover = () => {
          triggers[index].classList.remove("pulseNeon");
        };
        trigger.addEventListener("mouseenter", addHover);
        trigger.addEventListener("mouseleave", removeHover);
      }
    },
    faq: function () {
      const triggers = document.querySelectorAll(".faqButton");
      const triggerArray = Array.from(triggers).entries();
      const faqContent = document.querySelectorAll("#faqContent");

      for (let [index, trigger] of triggerArray) {
        const toggleModal = () => {
          if (faqContent[index].classList.contains("hidden")) {
            faqContent[index].classList.replace("hidden", "block");
          } else if (faqContent[index].classList.contains("block")) {
            faqContent[index].classList.replace("block", "hidden");
          }
        };
        trigger.addEventListener("click", toggleModal);
      }
    },
  },
  beforeMount() {
    this.hoverItem();
    this.faq();
  },
};
</script>
