<template>
    <section class="mx-auto px-8 bg-gray-900">
      <div class="grid grid-cols-2 gap-4 flex items-center">
        <div>
          <p
            class="mb-4 font-extrabold tracking-tight leading-none text-white"
          >
            Partner With An Expert To Help Build Your Business
          </p>
          <h1
            class="mb-4 text-2xl font-extrabold tracking-tight leading-none text-white md:text-3xl lg:text-5xl"
          >
          Discover A Better Way To Generate Leads With Our Website Design And Automation Solutions
          </h1>
          <p
            class="mb-8 text-lg font-normal text-gray-500 lg:text-xl"
          >
          Automate your lead generation process with our expert website design services. Our experienced team can create a website that captures and nurtures leads automatically, while you focus on growing your business. Don't let your competition get ahead - contact us today to learn how we can help you save time and increase your chances of converting visitors into loyal customers. Take your business to the next level with our website design and automation services.
          </p>

          

          <CardDeckThreeColumns>
            <Card 
              title="Revamp Your Lead Generation"
              description="Revolutionize your lead generation process."
            />
            <Card 
              title="Website Design Solutions"
              description="Increase your chances of converting visitors into customers."
            />
            <Card 
              title="Elevate Your Business"
              description="Take your business to the next level with automation."
            />
          </CardDeckThreeColumns>
        
          <div
            class="flex flex-col space-y-4 sm:flex-row sm:justify-left sm:space-y-0 sm:space-x-4"
          >
            <button
              type="button"
              class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
            >
                Get Started Now!
            </button>
          </div>
        </div>

        <div class="self-end">
          <img src="~/assets/images/temp-man.png" />
        </div>
      </div>
    </section>
</template>

<script>
export default {
  name: "HeroSection",
};
</script>

<style scoped>
</style>