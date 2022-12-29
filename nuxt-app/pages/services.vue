<template>
  <main
    class="relative shadow-top shadow-bottom lg:rounded-2xl lg:mr-[3.333%] 2xl:mr-[10.333%] lg:place-self-end 2xl:place-self-center h-screen lg:max-h-[90%] xl:max-h-[80%] w-full lg:max-w-[80%] xl:max-w-[80%] 2xl:max-w-[70%] 2xl:max-h-[80%] my-auto xl:ml-[12.2222%] 2xl:mx-auto transition-all duration-150 lg:border-4 border-purple-500/30 shadow-2xl shadow-purple-500/50 bg-black/10 lg:bg-black/30 backdrop-blur overflow-y-auto"
  >
    <Head>
      <Title>Services</Title>
    </Head>
    <div
      class="w-full grid grid-cols-1 lg:grid-cols-2 place-items-start place-content-start p-5 lg:px-10 lg:pt-5 z-10 preserve-3d bg-gradient-to-r from-purple-500/30 to-blue-500/10 rounded-b-2xl shadow-2xl shadow-purple-500/20"
    >
      <div class="grid place-items-start">
        <h1
          class="text-3xl md:text-4xl font-black text-shadow pulseNeon bg-clip-text text-white/50"
        >
          Services
        </h1>
      </div>
      <div class="hidden lg:flex self-center justify-self-end">
        <nuxt-link to="/contact">
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
    <div class="grid p-5 lg:p-10">
      <div class="my-10">
        <h3 class="text-3xl xl:text-4xl text-white font-black">
          We can create for you something
          <span
            class="bg-gradient-to-r from-blue-500/50 to-purple-500/50 p-2 text-white uppercase rounded-xl text-shadow pulseNeon text-lg xl:text-xl 2xl:text-3xl font-black"
            >exceptional</span
          >
        </h3>
        <p
          class="text-white/80 break-words md:text-lg lg:text-lg my-5 font-bold lg:max-w-2xl"
        >
          Thanks to modern technology and experience which has our team, we can
          provide you with services to develop from scratch (or not), various
          types of websites, such as those shown below.
          <span
            class="box-decoration-clone break-words shadow-top shadow-bottom p-[3px] text-white/80 rounded-xl"
            >Also we provide services to redesign your website, all details we
            can discuss in person.</span
          >
        </p>
      </div>
      <div
        class="grid lg:grid-cols-3 xl:grid-cols-3 2xl:grid-cols-4 gap-5 place-items-center"
      >
        <aside
          class="shadow-top grid place-self-start place-content-start col-span-1 shadow-bottom rounded-2xl w-full break-words bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-3 2xl:p-5 transition-all duration-150"
        >
          <div>
            <h3 class="mb-5 lg:text-lg 2xl:text-xl text-white font-black">
              Extended services
            </h3>
          </div>
          <div class="flex flex-col items-start">
            <h4
              class="box-decoration-clone break-words text-base font-black bg-gradient-to-r from-blue-500/30 to-purple-500/30 p-2 text-white rounded-xl"
            >
              Free services:
            </h4>
            <div>
              <ul
                class="mt-2 list-none text-white/80 break-words text-base font-bold"
              >
                <li
                  class="before:2xl:text-2xl before:content-['👌'] before:pr-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words lg:text-sm 2xl:text-base font-bold my-2"
                  >
                    Basic Support
                    <button
                      data-popover-target="popover-description-1"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-1"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3
                        class="font-black text-white/80 lg:text-sm 2xl:text-base"
                      >
                        Basic Support
                      </h3>
                      <p class="text-base font-medium">
                        Basic support includes 2 weeks of free technical support
                        for your site after the submission of the project, if
                        you are interested in a longer support period, you can
                        arrange for extended support.
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
                <li
                  class="before:2xl:text-2xl before:content-['👌'] before:pr-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words text-base font-bold my-2"
                  >
                    Consultation
                    <button
                      data-popover-target="popover-description-2"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-2"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3
                        class="font-black text-white/80 lg:text-sm 2xl:text-base"
                      >
                        Consultation step by step
                      </h3>
                      <p class="text-base font-medium">
                        We consult at every stage of project development, so
                        that there are no blind spots and misunderstandings.
                      </p>
                      <h3 class="font-black text-white/80 text-lg lg:text-xl">
                        What first?
                      </h3>
                      <p class="text-base font-medium">
                        After reviewing your project, desires, as well as
                        competitors, we can make a preliminary conclusion about
                        what to offer you, the timing of development and a
                        preliminary cost of the project.
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
                <li
                  class="before:2xl:text-2xl before:content-['👌'] before:pr-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words text-base font-bold my-2"
                  >
                    Simple prototype
                    <button
                      data-popover-target="popover-description-3"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-3"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3
                        class="font-black text-white/80 lg:text-sm 2xl:text-base"
                      >
                        Prototype in Figma
                      </h3>
                      <p class="text-base font-medium">
                        Creating a set of basic site features with a minimal
                        design that will need to help you understand how the
                        product will further solve the customer's problem. It's
                        like bold strokes on a canvas, with each step refining
                        the details.
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
                <h4
                  class="inline-block mt-2 box-decoration-clone break-words text-base font-black bg-gradient-to-r from-blue-500/30 to-purple-500/30 p-2 text-white rounded-xl"
                >
                  Paid services:
                </h4>
                <li
                  class="before:2xl:text-2xl before:content-['🤑'] before:pr-2 mt-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words lg:text-sm 2xl:text-base font-bold my-2"
                  >
                    MVP
                    <button
                      data-popover-target="popover-description-4"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-4"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3
                        class="font-black text-white/80 lg:text-sm 2xl:text-base"
                      >
                        Minimal Viable Product - MVP
                      </h3>
                      <p class="text-base font-medium">
                        Once your idea has been implemented as a prototype, it's
                        time to develop ideas. Functionality, realibility,
                        usability, and finally exceptional design.
                        <span class="inline-block mt-2">
                          The purpose of creating an MVP is to understand the
                          categories of major customers, their needs, to offer a
                          solution.
                          <span class="inline-block mt-2">
                            This is actually a very important stage of product
                            development, before moving on to the next stage of
                            the MMP.
                          </span>
                        </span>
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
                <li
                  class="before:2xl:text-2xl before:content-['🤑'] before:pr-2 mt-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words lg:text-sm 2xl:text-base font-bold my-2"
                  >
                    MMP
                    <button
                      data-popover-target="popover-description-5"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-5"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3
                        class="font-black text-white/80 lg:text-sm 2xl:text-base"
                      >
                        Minimum Marketable Product
                      </h3>
                      <p class="text-base font-medium">
                        After MVP development we will better understand what the
                        client needs and what can be improved.
                        <span class="inline-block mt-2">
                          MVP will help us understand if we should develop the
                          product further, or if we can launch the project to a
                          wider market at the MVP stage.
                        </span>

                        <span class="inline-block mt-2">
                          In principle, at the MVP stage we can launch the site
                          for a limited number of users, then the first users
                          will help us understand the flaws in the product and
                          where there are points that need to be improved.
                        </span>
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
                <li
                  class="before:2xl:text-2xl before:content-['🤑'] before:pr-2 mt-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words lg:text-sm 2xl:text-base font-bold my-2"
                  >
                    Template layout
                    <button
                      data-popover-target="popover-description-6"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-6"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3 class="font-black text-white/80 text-lg lg:text-xl">
                        Web site layout by design
                      </h3>
                      <p class="text-base font-medium">
                        The layout of the site according to your or my design
                        from Figma, includes standard HTML layout, or
                        component-oriented Vue.js layout.
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
                <li
                  class="before:2xl:text-2xl before:content-['🤑'] before:pr-2 mt-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words lg:text-sm 2xl:text-base font-bold my-2"
                  >
                    Extended functional
                    <button
                      data-popover-target="popover-description-7"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-7"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3 class="font-black text-white/80 text-lg lg:text-xl">
                        Additional features
                      </h3>
                      <p class="text-base font-medium">
                        Extended functionality implies additional refinements to
                        the standard components of the site, such as a shopping
                        cart in the online store or product cards, as well as
                        the development of new non-standard functionality for
                        your website.
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
                <li
                  class="before:2xl:text-2xl before:content-['🤑'] before:pr-2 mt-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words lg:text-sm 2xl:text-base font-bold my-2"
                  >
                    Extended support
                    <button
                      data-popover-target="popover-description-8"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-8"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3 class="font-black text-white/80 text-lg lg:text-xl">
                        Extended technical support
                      </h3>
                      <p class="text-base font-medium">
                        Once the project is delivered, I offer extended
                        technical support for a certain price per month, which
                        is much lower than if you were looking for another
                        developer to solve your needs.
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
                <li
                  class="before:2xl:text-2xl before:content-['🤑'] before:pr-2 mt-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words lg:text-sm 2xl:text-base font-bold my-2"
                  >
                    Domain & Hosting
                    <button
                      data-popover-target="popover-description-9"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-9"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3 class="font-black text-white/80 text-lg lg:text-xl">
                        Domain & Hosting at a discount
                      </h3>
                      <p class="text-base font-medium">
                        Domain and hosting from my partners at a discount
                        especially for dear customers 😃
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
                <li
                  class="before:2xl:text-2xl before:content-['🤑'] before:pr-2 mt-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words lg:text-sm 2xl:text-base font-bold my-2"
                  >
                    SEO promotion
                    <button
                      data-popover-target="popover-description-10"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-10"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3 class="font-black text-white/80 text-lg lg:text-xl">
                        Promoting your website
                      </h3>
                      <p class="text-base font-medium">
                        Seo promotion will help you find customers, help with
                        positioning in a niche of your business, without it you
                        just can't sell your product.
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
                <li
                  class="before:2xl:text-2xl before:content-['🤑'] before:pr-2 mt-2"
                >
                  <div
                    class="inline-flex text-white/80 break-words lg:text-sm 2xl:text-base font-bold my-2"
                  >
                    Content production
                    <button
                      data-popover-target="popover-description-11"
                      data-popover-placement="bottom-end"
                      type="button"
                    >
                      <svg
                        class="w-4 h-4 ml-2 text-white/80 hover:text-white"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                          clip-rule="evenodd"
                        ></path></svg
                      ><span class="sr-only">Show information</span>
                    </button>
                  </div>
                  <div
                    data-popover
                    id="popover-description-11"
                    role="tooltip"
                    class="absolute z-10 invisible inline-block text-sm font-light text-white/80 transition-all duration-[1ms] break-words bg-gradient-to-r from-blue-500/95 to-purple-500/95 rounded-lg shadow-sm opacity-0 hover:shadow-2xl hover:shadow-indigo-500 backdrop-blur-3xl"
                  >
                    <div class="p-3 space-y-2 max-w-sm">
                      <h3 class="font-black text-white/80 text-lg lg:text-xl">
                        Content production
                      </h3>
                      <p class="text-base font-medium">
                        Content for the site is very important, I can help you
                        with its development, my team is happy to help you with
                        text and media content, pictures videos, etc..
                      </p>
                    </div>
                    <div data-popper-arrow></div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </aside>
        <div
          class="grid lg:grid-cols-1 xl:grid-cols-2 2xl:grid-cols-3 lg:col-span-1 xl:col-span-2 2xl:col-span-3 gap-5 place-self-start"
        >
          <div
            class="grid place-self-start rounded-2xl h-full w-full lg:min-w-[300px] lg:min-h-[250px] break-words bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-5 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <div>
              <h3 class="text-xl xl:text-2xl text-white font-black">
                WordPress
                <span class="font-black text-white/80 pulseNeon">$300</span>
              </h3>
            </div>
            <div class="grid place-items-start row-span-3">
              <p class="text-white/80 break-words text-base xl:text-base my-4">
                Site on WordPress is suitable for different purposes, small and
                medium-sized online store, blog, portfolio. With a convenient
                management system that is suitable for beginners, a huge number
                of paid and free plugins and templates, WordPress is certainly
                the leader in the segment of CMS.
              </p>
            </div>
          </div>
          <div
            class="grid place-self-start rounded-2xl h-full w-full lg:min-w-[300px] lg:min-h-[250px] break-words bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-5 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <div>
              <h3 class="text-xl xl:text-2xl text-white font-black">
                Company
                <span class="font-black text-white/80 pulseNeon">$400</span>
              </h3>
            </div>
            <div class="grid place-items-start row-span-3">
              <p class="text-white/80 break-words text-base xl:text-base my-4">
                My team and I can develop a website for your company that
                Increase the reach of potential customers by introducing your
                product to a wider audience, now almost every company is trying
                to create a website and reach the maximum number of customers in
                their niche.
              </p>
            </div>
          </div>
          <div
            class="grid place-self-start rounded-2xl h-full w-full lg:min-w-[300px] lg:min-h-[250px] break-words bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-5 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <div>
              <h3 class="text-xl xl:text-2xl text-white font-black">
                Online store
                <span class="font-black text-white/80 pulseNeon">$500</span>
              </h3>
            </div>
            <div class="grid place-items-start row-span-3">
              <p class="text-white/80 break-words text-base xl:text-base my-4">
                We provide services to develop online stores from scratch, or
                using CMS such as WordPress, Shopify, Snipcart. If you are not
                sure what exactly you need, you can always ask me for a
                consultation, it is free.
              </p>
            </div>
          </div>
          <div
            class="grid place-self-start rounded-2xl h-full w-full lg:min-w-[300px] lg:min-h-[250px] break-words bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-5 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <div>
              <h3 class="text-xl xl:text-2xl text-white font-black">
                Hourly rate
                <span class="font-black text-white/80 pulseNeon">$12/h</span>
              </h3>
            </div>
            <div class="grid place-items-start row-span-3">
              <p class="text-white/80 break-words text-base xl:text-base my-4">
                An hourly rate is needed if your project does not have final
                approved design and features, or you have a proposal to
                collaborate on your project, the rate can be negotiated
                depending on the project.
              </p>
            </div>
          </div>
          <div
            class="grid place-self-start rounded-2xl h-full w-full lg:min-w-[300px] lg:min-h-[250px] break-words bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-5 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <div>
              <h3 class="text-xl xl:text-2xl text-white font-black">
                Landing page
                <span class="font-black text-white/80 pulseNeon">$200</span>
              </h3>
            </div>
            <div class="grid place-items-start row-span-3">
              <p class="text-white/80 break-words text-base xl:text-base my-4">
                Suitable if you want to sell one or more products or services,
                as well as for a portfolio or a small company / startup.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="grid my-20">
        <div>
          <h3 class="text-3xl xl:text-4xl text-white font-black">
            How i work?
          </h3>
          <p
            class="text-white/80 break-words md:text-lg lg:text-lg my-5 font-bold lg:max-w-2xl"
          >
            As you have already understood, I am a freelancer, so relatively
            small projects I develop myself, although, of course, if the project
            is technically complex, I involve programmers from my team, thanks
            to this I can offer you a good final cost of the project.
          </p>
        </div>
        <div class="grid grid-cols-2 lg:grid-cols-4 mt-5 gap-2 xl:gap-5">
          <div
            class="2xl:place-self-start min-w-full bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-4 xl:p-5 rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <h3
              class="text-sm xl:text-lg text-white font-black before:content-['1'] before:pr-1.5 before:text-4xl before:text-white/50"
            >
              Problem
            </h3>
            <p
              class="text-white/80 break-words text-base my-5 font-light lg:max-w-2xl"
            >
              Search for potential project problems
            </p>
          </div>
          <div
            class="2xl:place-self-start min-w-full bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-4 xl:p-5 rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <h3
              class="text-sm xl:text-lg text-white font-black before:content-['2'] before:pr-1.5 before:text-4xl before:text-white/50"
            >
              Solution
            </h3>
            <p
              class="text-white/80 break-words text-base my-5 font-light lg:max-w-2xl"
            >
              Finding solutions to project problems
            </p>
          </div>
          <div
            class="2xl:place-self-start min-w-full bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-4 xl:p-5 rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <h3
              class="text-sm xl:text-lg text-white font-black before:content-['3'] before:pr-1.5 before:text-4xl before:text-white/50"
            >
              Potential Users
            </h3>
            <p
              class="text-white/80 break-words text-base my-5 font-light lg:max-w-2xl"
            >
              Searching for target customers of the project
            </p>
          </div>
          <div
            class="2xl:place-self-start min-w-full bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-4 xl:p-5 rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <h3
              class="text-sm xl:text-lg text-white font-black before:content-['4'] before:pr-1.5 before:text-4xl before:text-white/50"
            >
              Action Points
            </h3>
            <p
              class="text-white/80 break-words text-base my-5 font-light lg:max-w-2xl"
            >
              Development of a roadmap for project development
            </p>
          </div>
          <div
            class="bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-4 xl:p-5 rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <h3
              class="text-sm xl:text-lg text-white font-black before:content-['5'] before:pr-1.5 before:text-4xl before:text-white/50"
            >
              Success Goal
            </h3>
            <p
              class="text-white/80 break-words text-base my-5 font-light lg:max-w-2xl"
            >
              Defining project goals
            </p>
          </div>
          <div
            class="bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-4 xl:p-5 rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <h3
              class="text-sm xl:text-lg text-white font-black before:content-['6'] before:pr-1.5 before:text-4xl before:text-white/50"
            >
              Architecture
            </h3>
            <p
              class="text-white/80 break-words text-base my-5 font-light lg:max-w-2xl"
            >
              Defining of project technologies
            </p>
          </div>
          <div
            class="2xl:place-self-start min-w-full bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-4 xl:p-5 rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <h3
              class="text-sm xl:text-lg text-white font-black before:content-['7'] before:pr-1.5 before:text-4xl before:text-white/50"
            >
              Project development
            </h3>
            <p
              class="text-white/80 break-words text-base my-5 font-light lg:max-w-2xl"
            >
              Front-end, Framework, Back-end
            </p>
          </div>
          <div
            class="2xl:place-self-start min-w-full bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-4 xl:p-5 rounded-2xl transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <h3
              class="text-sm xl:text-lg text-white font-black before:content-['8'] before:pr-1.5 before:text-4xl before:text-white/50"
            >
              Finul result
            </h3>
            <p
              class="text-white/80 break-words text-base my-5 font-light lg:max-w-2xl"
            >
              Final result, submission of the project to the customer
            </p>
          </div>
        </div>
      </div>
      <div
        class="shadow-top shadow-bottom grid 2xl:grid-cols-2 place-content-start mb-10 lg:mb-0 w-full 2xl:place-items-center rounded-2xl break-words bg-gradient-to-r from-blue-500/30 to-purple-500/10 p-4 lg:p-10 my-10 transition-all duration-150"
      >
        <div class="grid place-items-start 2xl:mx-auto max-w-2xl">
          <div class="lg:min-w-max">
            <h3 class="text-3xl xl:text-4xl text-white font-black pulseNeon">
              Just write to me to get started
            </h3>
          </div>
          <p
            class="text-white/80 break-words font-bold md:text-lg lg:text-md text-left py-5"
          >
            By choosing us you bet on young and talented people, we love our
            business and with every project we strive to jump over the top, to
            go beyond templates and standards wherever possible. We will
            actively guide you from the beginning of the collaboration to its
            release, because it's our baby that will see the world, it's our
            reputation. Let's do something incredible together
            <span class="pulseNeon text-lg">😎🔥</span>
          </p>
          <p
            class="text-white/80 font-base text-sm max-w-lg text-left bg-gradient-to-r from-blue-500/30 to-purple-500/10 rounded-lg p-5 my-5"
          >
            * The price is listed as initial, it may change depending on the
            complexity of the project.
          </p>
          <nuxt-link
            id="hoverItem"
            to="/contact"
            class="text-white text-center py-3 px-5 mt-5 w-[150px] transition-all duration-150 rounded-lg text-sm bg-gradient-to-r from-purple-500/30 to-blue-500/10 hover:shadow-2xl hover:shadow-indigo-500"
            >Get started</nuxt-link
          >
        </div>
        <div
          class="grid grid-cols-2 lg:grid-cols-4 2xl:grid-cols-2 place-content-center text-center place-self-center gap-5 lg:gap-8 mt-10 mb-10 lg:mb-0 lg:mt-10 2xl:mt-0 text-white"
        >
          <div
            class="grid place-items-center bg-gradient-to-r from-blue-500/30 to-purple-500/10 rounded-lg p-3 lg:p-5 xl:p-5 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <div>
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path d="M14 11H10V13H14V11Z" fill="currentColor" />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M7 5V4C7 2.89545 7.89539 2 9 2H15C16.1046 2 17 2.89545 17 4V5H20C21.6569 5 23 6.34314 23 8V18C23 19.6569 21.6569 21 20 21H4C2.34314 21 1 19.6569 1 18V8C1 6.34314 2.34314 5 4 5H7ZM9 4H15V5H9V4ZM4 7C3.44775 7 3 7.44769 3 8V14H21V8C21 7.44769 20.5522 7 20 7H4ZM3 18V16H21V18C21 18.5523 20.5522 19 20 19H4C3.44775 19 3 18.5523 3 18Z"
                  fill="currentColor"
                />
              </svg>
            </div>
            <div
              class="p-2 text-sm xl:text-lg xl:font-black text-white my-2 xl:my-0"
            >
              <h4>Done projects</h4>
            </div>
            <div class="text-xl font-black text-white/80">25+</div>
          </div>
          <div
            class="grid place-items-center bg-gradient-to-r from-blue-500/30 to-purple-500/10 rounded-lg p-3 lg:p-5 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <div>
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M12 19C10.067 19 8.31704 18.2165 7.05029 16.9498L12 12L12 5C15.866 5 19 8.13401 19 12C19 15.866 15.866 19 12 19Z"
                  fill="currentColor"
                />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12C1 5.92487 5.92487 1 12 1C18.0751 1 23 5.92487 23 12ZM21 12C21 16.9706 16.9706 21 12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3C16.9706 3 21 7.02944 21 12Z"
                  fill="currentColor"
                />
              </svg>
            </div>
            <div
              class="p-2 text-sm xl:text-lg xl:font-black text-white my-2 xl:my-0"
            >
              <h4>Developming</h4>
            </div>
            <div class="text-xl font-black text-white/80">3Y+</div>
          </div>
          <div
            class="grid place-items-center bg-gradient-to-r from-blue-500/30 to-purple-500/10 rounded-lg p-3 lg:p-5 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <div>
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 21.5L17.5 13L13 10L15 2.5L6.5 11L11 14L9 21.5Z"
                  fill="currentColor"
                />
              </svg>
            </div>
            <div
              class="p-2 text-sm xl:text-lg xl:font-black text-white my-2 xl:my-0"
            >
              <h4>Technologies</h4>
            </div>
            <div class="text-xl font-black text-white/80">7+</div>
          </div>
          <div
            class="grid place-items-center bg-gradient-to-r from-blue-500/30 to-purple-500/10 rounded-lg p-3 lg:p-5 transition-all duration-150 hover:shadow-2xl hover:shadow-indigo-500"
          >
            <div>
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path d="M14 11H10V13H14V11Z" fill="currentColor" />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M7 5V4C7 2.89545 7.89539 2 9 2H15C16.1046 2 17 2.89545 17 4V5H20C21.6569 5 23 6.34314 23 8V18C23 19.6569 21.6569 21 20 21H4C2.34314 21 1 19.6569 1 18V8C1 6.34314 2.34314 5 4 5H7ZM9 4H15V5H9V4ZM4 7C3.44775 7 3 7.44769 3 8V14H21V8C21 7.44769 20.5522 7 20 7H4ZM3 18V16H21V18C21 18.5523 20.5522 19 20 19H4C3.44775 19 3 18.5523 3 18Z"
                  fill="currentColor"
                />
              </svg>
            </div>
            <div
              class="p-2 text-sm xl:text-lg xl:font-black text-white my-2 xl:my-0"
            >
              <h4>Sales growth</h4>
            </div>
            <div class="text-xl font-black text-white/80">1000%+</div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  head: {
    script: [
      {
        src: "/assets/js/flowbite.js",
        async: true,
        defer: true,
        crossorigin: "anonymous",
      },
    ],
  },
  mounted() {
    (function () {
      if (window.localStorage) {
        if (!localStorage.getItem("firstLoad")) {
          localStorage["firstLoad"] = true;
          setTimeout(() => {
            window.location.reload();
          }, 1100);
        } else localStorage.removeItem("firstLoad");
      }
    })();
  },
};
</script>
