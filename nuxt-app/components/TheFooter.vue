<template>
    <footer class="bg-stone-900 mt-auto py-10">
      <div class="grid place-items-center grid-cols-2">
        <div>
         <NuxtLink to="/"><h3 class="text-xl uppercase font-bold text-center text-stone-300">Vratskyi</h3></NuxtLink> 
        </div>
  
        <ul
          class="grid grid-flow-col place-content-end text-md p-4 text-stone-300"
        >
          <li>
            <NuxtLink to="/" class="hover:underline hover:underline-offset-4"
              >Home</NuxtLink
            >
          </li>
          <li>
            <NuxtLink to="/about" class="hover:underline hover:underline-offset-4"
              >About</NuxtLink
            >
          </li>
          <li>
          <NuxtLink to="/portfolio" class="hover:underline hover:underline-offset-4"
            >Portfolio</NuxtLink
          >
        </li>
        <li>
          <NuxtLink to="/services" class="hover:underline hover:underline-offset-4"
            >Services</NuxtLink
          >
        </li>
        <li>
          <NuxtLink to="/contact" class="hover:underline hover:underline-offset-4"
            >Contact</NuxtLink
          >
        </li>
        </ul>
      </div>
    </footer>
  </template>
  