<template>
  <div
    class="h-screen bg-[url('https://images.unsplash.com/photo-1564510714747-69c3bc1fab41?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D')] bg-cover bg-center relative flex flex-col justify-center px-4 xl:px-12"
  >
    <div class="bg-black/50 absolute inset-0 z-0" ></div>
    <div class="absolute left-0 top-0 w-full"><HeaderComponent /></div>

    <h4 class="text-white text-4xl xl:text-7xl z-10 xl:w-5/6 mt-24 mb-6 leading-tight xl:leading-tight">
      Embrace Productivity and Habits: Unlock Your Full Potential Every Day
    </h4>

    <div class="z-10">
      <input
        type="text"
        placeholder="Search An Article"
        class="rounded-full w-56 xl:w-80 py-1.5 px-4 focus:outline-none"
      />
      <button class="ml-4 rounded-full font-semibold bg-white/80 py-1.5 px-6 text-green-800">
        Search
      </button>
    </div>
  </div>
</template>

<script setup>
import HeaderComponent from "./HeaderComponent.vue";
</script>