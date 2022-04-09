<template>
  
  <div class="herobgImage bg-cover bg-center relative">
    <!-- Background Opacity -->
    <div 
      class="bg-black opacity-70 w-full h-full absolute">
    </div>

    <!-- Hero Text -->
    <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
      <div class="max-w-md sm:max-w-2xl">
        <h3 class="text-gray-200 tracking-widest">
          <!-- Mobile Upper Header -->
          <span class="block lg:hidden">CHICAGO CAR DETAILING </span>
          <span class="block lg:hidden">& AUTO SERVICES</span>
          <!-- Desktop Upper Header -->
          <span class="hidden lg:block">CHICAGO CAR DETAILING & AUTO SERVICES</span>
        </h3>
        <h1 class="text-white text-4xl font-extrabold tracking-tight lg:py-1 xl:py-0">
          <!-- Mobile Header Text-->
          <span class="block xl:hidden">SCHEDULE</span>
          <span class="flex flex-col xl:hidden">SERVICES ONLINE</span>
          <!-- Desktop Header Text -->
          <span class="hidden xl:block">SCHEDULE SERVICES ONLINE</span>
          <span class="hidden lg:block text-red-700">WITH A FEW CLICKS.</span>
        </h1>
        <p class="text-gray-200 font-thin tracking-wide">
          <!-- Mobile Lower Text -->
          <span class="block lg:hidden">We offer services for cars,</span>
          <span class="block lg:hidden">boats, planes, and more.</span>
          <!-- Desktop Lower Text -->
          <span class="hidden lg:block">We offer services for cars, boats, planes, and more.</span>
          <span class="block pb-1">Click below to schedule today.</span>
        </p>
        <div class="pt-5">
          <a href="#" 
            class="px-16 sm:px-20 lg:px-32 py-3 border border-transparent shadow-sm text-sm font-medium text-white bg-red-700 hover:bg-red-800 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-black focus:ring-red-700">
            Schedule <span class="hidden lg:inline-block">Here</span>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Brand Logos -->
  <div class="brandLogos bg-gray-100">
    <div class="h-full mx-auto">
      <span class="w-11/12 md:w-4/5 lg:w-3/5 h-full mx-auto border-b-2 border-gray-200 flex justify-evenly items-center">
        <img class="h-20 w-20 md:h-24 md:w-24" src="../static/icons8-infiniti.svg" alt="">
        <img class="h-20 w-20 md:h-24 md:w-24" src="../static/icons8-lamborghini.svg" alt="">
        <img class="h-20 w-20 md:h-24 md:w-24" src="../static/icons8-hyundai.svg" alt="">
        <img class="h-20 w-20 md:h-24 md:w-24" src="../static/icons8-honda.svg" alt="">
        <img class="h-20 w-20 md:h-24 md:w-24" src="../static/icons8-toyota.svg" alt="">
      </span>
    </div>
  </div>
</template>

<style>

  .herobgImage {
    background-image: url("/src/static/HeroImage.jpg");
    height:80vh;
  }

  .brandLogos {
    height:20vh;
  }

</style>