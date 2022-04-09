<template>
  <div class="bg-gray-100 relative flex flex-col items-center justify-center shadow-sm" id="AboutSection">
    <!-- Upper Text & Image -->
    <div class="flex flex-col lg:flex-row items-center justify-center">

      <!-- Upper Text -->
      <div class="lg:mr-20 lg:pt-10">
        <h3 class="text-gray-600 lg:text-lg text-sm">Chicago Automotive Services</h3>
        <h1 class="text-gray-900 text-3xl lg:text-4xl border-b-2 border-gray-200 pb-5">
          We focus on providing
          <span class="block font-bold text-red-700">the highest quality</span>
          automative services.
          </h1>
        <p class="w-full mx-auto pt-5 lg:text-lg">
          <span class="block">You can depend on our experts to take great</span> 
          <span class="block">care of you. We approach our clients with the</span>
          <span class="block">best care. We treat cars with incredible care.</span>
          <span class="block">More on how to contact us and schedule an</span>
          <span class="block">appointment below.</span>
        </p>
      </div>
      <!-- Image -->
      <div class="pt-14">
        <img class="h-80 w-80 lg:h-96 lg:w-96 shadow-md" src="../static/AboutImage.jpg" alt="">
      </div>

    </div>
  </div>
</template>

<script>

export default {

  name: 'AboutSection',

  setup() {
    return {

    }
  },
}
</script>

<style>

  #AboutSection {
    height: 95vh;
  }

</style>