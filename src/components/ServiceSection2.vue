<template>
    <div class="serviceBg2 bg-black">
        <div class="">
            <div class="pt-10 pb-16 lg:pl-20 xl:pl-40 2xl:pl-60">
                <h3 class="text-gray-200 tracking-widest text-sm lg:text-left">Chicago Automotive Services</h3>
                <h1 class="text-3xl lg:text-4xl uppercase lg:text-left">
                    <span class="block text-gray-100 md:inline-block md:mr-2">Striving for</span>
                    <span class="block text-red-700 font-bold md:inline-block">perfection</span>
                </h1>
            </div>
            <hr class="border-b border-gray-200 w-2/3 lg:w-11/12 xl:w-5/6 mx-auto">
            <div class="lg:flex justify-center">
                <div class="mt-16 mb-10 lg:mr-20 xl:mr-40 2xl:mr-60 flex flex-col space-y-20 lg:space-y-12">
                    <div class="mx-auto">
                        <h2 class="text-gray-200 tracking-widest text-lg lg:text-xl mb-3">Popular Services</h2>
                        <p class="text-gray-300 mx-auto mb-3">
                            <span class="block">We are not limited to these, but here are a few </span>
                            <span class="block">examples of our most popular services. If you are </span>
                            <span class="block">interested in any of these, just mention them when </span>
                            <span class="block">scheduling an appointment.</span>
                        </p>
                        <div class="text-gray-300 w-max mx-auto lg:text-lg">
                            <div class="flex items-center">
                                <i class="fa-solid fa-circle-check mr-2"></i>
                                <h2>Car Wrapping</h2>
                            </div>
                            <div class="flex items-center">
                                <i class="fa-solid fa-circle-check mr-2"></i>
                                <h2>Window Tint</h2>
                            </div>
                            <div class="flex items-center">
                                <i class="fa-solid fa-circle-check mr-2"></i>
                                <h2>Auto Detail</h2>
                            </div>
                        </div>
                    </div>
                    <!-- List of a few services -->
                    <div class="mx-auto">
                        <h2 class="text-gray-200 tracking-widest text-lg lg:text-xl mb-3">Trust Professionals</h2>
                        <p class="text-gray-300 mb-5">
                            <span class="block">You can depend on our experts to take great care </span>
                            <span class="block">of you. We approach our clients with the best </span>
                            <span class="block">experts. We treat cars with incredible care. More </span>
                            <span class="block">on how to contact us and how to schedule an </span> 
                            <span class="block">appointment below. Come see what sets us apart.</span>  
                        </p>
                        <!-- Appointment Button -->
                        <a href="#" 
                            class="px-20 py-3 border border-transparent shadow-sm text-sm font-medium text-white bg-red-700 hover:bg-red-800 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-black focus:ring-red-700">
                            Schedule Here
                        </a>
                    </div>
                </div>
                <!-- Image -->
                <div class="hidden lg:block mt-16">
                    <img class="serviceBgImage" src="../static/Service2Bg.jpg" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style>

    .serviceBg2 {
        height:95vh;
    }

    .serviceBgImage {
        height:500px;
    }

</style>