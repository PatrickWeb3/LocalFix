<template>
  <div class="ctaBg bg-cover bg-center relative">
    <!-- Background Opacity -->
    <div 
      class="bg-black opacity-70 w-full h-full absolute">
    </div>

    <div class="max-w-2xl bg-gray-200 absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-2/3 mx-auto">
      <div class="max-w-2xl mx-auto text-center py-16 px-4 sm:py-20 sm:px-6 lg:px-8">
        <h2 class="text-3xl text-gray-900 sm:text-4xl uppercase">
          <span class="block">Schedule with</span>
          <span 
            class="block font-bold text-red-700">
            Excellence
            <span class="hidden lg:inline-block">Today</span>
          </span>
        </h2>
        <div class="mt-5">
          <i class="text-red-700 text-4xl fa-solid fa-circle-arrow-down"></i>
        </div>
        <div class="mt-10">
          <a href="#" 
            class="px-16 sm:px-20 lg:px-32 py-3 border border-transparent shadow-sm text-sm font-medium text-white bg-red-700 hover:bg-red-800 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-black focus:ring-red-700">
            Contact Us<span class="hidden lg:inline-block lg:ml-1">Today</span>
          </a> 
        </div>   
      </div>
    </div>
  </div>
  
</template>

<style>

  .ctaBg {
    background-image: url("/src/static/calltoaction2.jpg");
    height:70vh;
  }

</style>