<script setup lang="ts"></script>

<template>
  <section class="bg-white min-h-screen sm:pb-20">
    <div
      class="grid lg:max-w-screen-2xl sm:max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12 h-screen">
      <div class="mr-auto place-self-center lg:col-span-4">
        <h1 class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl">
          Payments tool for software companies
        </h1>
        <p class="max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl">
          From checkout to global sales tax compliance, companies around the world use Nobit to simplify their payment
          stack.
        </p>
        <a
          href="http://www.w3.org/2000/svg"
          class="inline-flex items-center justify-center px-5 py-3 mr-3 text-base font-medium text-center text-white rounded-lg bg-lime-600 bg-gradient-to-r hover:bg-lime-800 focus:ring-4 focus:ring-primary-300">
          Get started
          <svg class="w-5 h-5 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path
              fill-rule="evenodd"
              d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
              clip-rule="evenodd" />
          </svg>
        </a>
        <a
          href="http://www.w3.org/2000/svg"
          class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100">
          Speak to Sales
        </a>
      </div>

      <div class="hidden lg:mt-0 lg:col-span-8 sm:col-span-6 lg:flex">
        <img src="../assets/images/image-mockups.png" class="lg:hidden block" alt="mockup" />
        <img class="hidden sm:block" src="../assets/images/image-mockups.png" alt="mockup" />
      </div>
    </div>
  </section>
</template>
