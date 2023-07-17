<template>
  <section class="container mx-auto mt-20">
    <div class="grid grid-cols-2 gap-4 items-center" v-if="mediaFirst">
      <div>
        <p
          class="mb-4 font-extrabold tracking-tight leading-none text-gray-900 dark:text-white"
        >
          {{ subTitle }}
        </p>
        <h1
          class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white"
        >
          {{ title }}
        </h1>
        <p
          class="mb-8 text-lg font-normal text-gray-500 lg:text-xl dark:text-gray-400"
        >
          {{ description }}
        </p>
        <div
          class="flex flex-col mb-8 lg:mb-16 space-y-4 sm:flex-row sm:justify-left sm:space-y-0 sm:space-x-4"
        >
          <button
            type="button"
            class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
          >
            Learn More About Our Program
          </button>
        </div>
      </div>
      <div>
        <nuxt-img
          format="webp"
          src="~/assets/images/contractor-marketing-program.jpg"
        />
      </div>
    </div>
    <div class="grid grid-cols-2 gap-4 items-center" v-else>
      <div>
        <img src="~/assets/images/contractor-marketing-program.jpg" />
      </div>
      <div>
        <p
          class="mb-4 font-extrabold tracking-tight leading-none text-gray-900 dark:text-white"
        >
          {{ subTitle }}
        </p>
        <h1
          class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white"
        >
          {{ title }}
        </h1>
        <p
          class="mb-8 text-lg font-normal text-gray-500 lg:text-xl dark:text-gray-400"
        >
          {{ description }}
        </p>
        <div
          class="flex flex-col mb-8 lg:mb-16 space-y-4 sm:flex-row sm:justify-left sm:space-y-0 sm:space-x-4"
        >
          <button
            type="button"
            class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
          >
            Learn More About Our Program
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TwoColumnSection",
  props: {
    title: String,
    description: String,
    mediaFirst: Boolean,
    subTitle: String,
  },
};
</script>

<style scoped>
</style>