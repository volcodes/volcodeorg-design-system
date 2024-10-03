<script setup lang="ts">
import Milestone from '@carbon/icons-vue/es/milestone/32';
import Modal from './components/Modal.vue'
</script>

<template>
  <div class="d-flex bg-slate-200">
    <header class="d-flex w-full pt-44 pb-4 px-28 bg-slate-950">
      <div class="container mx-auto">
        <h1 class="text-white text-left text-8xl container font-afacad font-semibold">Mehmet's Portfolio</h1>
        <p class="text-left text-gray-400 text-2xl container font-afacad pt-2 pb-6">I build web applications, improve workflows, and help teams create better digital solutions.</p>
      </div>
    </header>
    <nav class="bg-slate-950 border-solid border border-b-0 border-r-0 border-l-0 border-slate-700 px-28">
      <div class="container mx-auto justify-start flex">
        <a href="#" class="text-xl text-white font-afacad p-4 pr-12 border-t-4 bg-gray-800 ease-linear border-[#0062fe] hover:text-gray-50" style="line-height: 2; margin-top: -2px">Overview</a>
        <a href="#" class="text-xl text-white font-afacad font-normal transition-all ease-linear border-t-4 border-transparent p-4 pr-12 hover:bg-gray-800 hover:text-gray-50" style="line-height: 2; margin-top: -2px">About Me</a>
        <a href="#" class="text-xl text-white font-afacad font-normal transition-all ease-linear p-4 pr-12 border-t-4 border-transparent hover:bg-gray-800 hover:text-gray-50" style="line-height: 2; margin-top: -2px">Projects</a>
        <a href="#" class="text-xl text-white font-afacad font-normal transition-all ease-linear p-4 pr-12 border-t-4 border-transparent hover:bg-gray-800 hover:text-gray-50" style="line-height: 2; margin-top: -2px">Contact</a>
      </div>
    </nav>
    <section class="h-screen font-afacad">
      <div class="container mx-auto flex flex-col pt-12 text-black text-base text-left">

        <div class="grid grid-cols-[70%_30%] gap-4">
          <div class="flex justify-end items-center">
            <!-- <h2 class="text-6xl font-bold mb-6">Key Achievements</h2> -->
            <p class="text-2xl text-gray-500">I specialize in modernizing legacy systems, optimizing workflows, and mentoring aspiring developers to create high-quality solutions that enhance user experiences.</p>
          </div>
          <div class="flex justify-end items-center">
            <a href="#" class="flex ease-linear bg-[#0f62fe] w-fit hover:bg-[#0050E6] active:border border border-transparent active:border-white active:outline-2 active:outline-[0F62FE] active:outline">
              <span class="w-fit text-2xl font-afacad font-normal text-white px-6 py-4 pr-8">My Key Achievements</span>
              <div class="text-white px-6 py-4 pl-2">
                <Milestone />
              </div>
            </a>
            <!-- <Modal title="Test" /> -->
          </div>
          <!-- <div>
            <h3 class="text-4xl font-medium mt-4 mb-2">Software Development</h3>
            <p class="text-2xl text-gray-500">Led the modernization of key products, transitioning from outdated PHP frameworks to modern Vue.js and Nuxt.js, enhancing user experience and driving increased traffic and engagement.</p>
          </div>
          <div>
            <h3 class="text-4xl font-medium mt-4 mb-2">Testing and Workflow Improvements</h3>
            <p class="text-2xl text-gray-500">Improved internal workflows by establishing a comprehensive design system and introducing integration testing standards, resulting in faster development cycles and reduced errors across the development team.</p>
          </div>
          <div>
            <h3 class="text-4xl font-medium mt-4 mb-2">Mentorship</h3>
            <p class="text-2xl text-gray-500">Provided personalized mentoring and facilitated knowledge-sharing sessions, enabling junior developers to successfully transition into front-end roles and elevating the overall skill set of the engineering team. Optimized technical documentation: Developed clear technical documentation that improved developer onboarding and collaboration, ultimately leading to a more efficient and cohesive engineering environment.</p>
          </div>
          <div>
            <h3 class="text-4xl font-medium mt-4 mb-2">Extensive Experience</h3>
            <p class="text-2xl text-gray-500">Innovated content delivery solutions: Implemented cutting-edge technologies, such as a video player with HLS support, enhancing performance and accessibility for millions of users worldwide, significantly improving the company’s digital content delivery capabilities.</p>
          </div> -->
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
</style>
