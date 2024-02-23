<script setup>
// import TheWelcome from '../components/TheWelcome.vue'
</script>
<!-- h-[950px] 可以寫成這樣固定寬高 -->

<template>
  <main class="flex lg:flex-row flex-col ">
    <nav class="bg-slate-400 lg:h-lvh xl:w-80 md:h-20  flex flex-col justify-center items-center  ">
      <div class="bg-white lg:p-5 lg:mb-16">LOGO</div>
      <button class="bg-slate-300 lg:w-60 text-xl  lg:p-8 ">About</button>
      <button class="bg-slate-300 lg:w-60 text-xl  lg:p-8 ">Latest Events</button>
      <button class="bg-slate-300 lg:w-60 text-xl  lg:p-8 ">News</button>
    </nav>
    <div class="right-box bg-gray-800 h-[950px]  lg:h-lvh xl:w-full lg:w-full md:w-full  sm:w-full flex justify-center items-center  ">
      <div class="box-all bg-cyan-300 xl:h-4/6 md:h-4/6 xl:w-8/12 md:w-8/12  flex md:flex-wrap xl:flex-nowrap ">
        <div class="box bg-cyan-50  xl:h-full md:h-1/2 md:w-full  xl:w-4/12 xl:mr-2 md:mr-0 md:mb-2 w-full  ">888</div>
        <div class="box bg-cyan-50 xl:h-full md:h-1/2 xl:w-4/12 xl:mr-2  md:w-1/2">888</div>
        <div class="box bg-cyan-50 xl:h-full md:h-1/2 xl:w-4/12 md:w-1/2">888</div>
      </div>
    </div>
  </main>
</template>
