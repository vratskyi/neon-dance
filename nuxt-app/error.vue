<template>
  <NuxtLayout name="default" class="flex flex-col text-center">
    <div
      class="relative shadow-top shadow-bottom lg:rounded-2xl grid grid-cols-1 lg:mr-[3.333%] 2xl:mr-[10.333%] place-content-center lg:place-self-end 2xl:place-self-center h-screen lg:max-h-[90%] xl:max-h-[80%] w-full lg:max-w-[80%] xl:max-w-[80%] 2xl:max-w-[70%] 2xl:max-h-[80%] my-auto xl:ml-[12.2222%] 2xl:mx-auto transition-all duration-300 lg:border-4 border-purple-500/30 shadow-2xl shadow-purple-500/50 bg-black/10 lg:bg-black/30 md:backdrop-blur"
    >
      <p
        class="main-title font-black uppercase text-shadow neonText bg-clip-text text-white/50 mb-4"
      >
        {{ error.statusCode }}
      </p>
      <p
        class="text-2xl md:text-3xl lg:text-4xl 2xl:text-4xl mt-5 font-bold text-shadow pulseNeon bg-clip-text text-white/50"
      >
        Wow.. we can't do this..
      </p>
      <p
        class="text-xl md:text-2xl lg:text-3xl 2xl:text-4xl mt-3 font-bold text-shadow pulseNeon bg-clip-text text-white/50"
      >
        {{ error.message }}
      </p>
      <button
        @click="handleClearError"
        class="grid place-self-center text-white/80 text-center py-3 px-5 mt-14 w-[150px] transition-all duration-150 rounded-lg text-sm bg-gradient-to-r from-purple-500/30 to-blue-500/10 hover:shadow-2xl hover:shadow-indigo-500"
      >
        Back to Home
      </button>
    </div>
  </NuxtLayout>
</template>

<script setup>
defineProps(["error"]);
const handleClearError = () => clearError({ redirect: "/" });
</script>
