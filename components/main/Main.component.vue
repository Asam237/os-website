<template>
  <main class="px-4 py-12">
    <div class="container mx-auto md:mt-8">
      <div class="flex flex-col md:flex-row">
        <div class="w-full md:w-1/2 text-center md:text-left">
          <h1
            style="font-family: 'Pacifico', cursive"
            class="text-[45px] md:text-[65px] leading-[70px]"
          >
            Think<span class="text-orange-600">.</span> Make<span
              class="text-orange-600"
              >.</span
            ><br />
            Solve<span class="text-orange-600">.</span>
          </h1>
          <div
            class="mt-4 md:mt-6 flex items-center justify-center md:justify-start"
          >
            <div class="w-12 h-[2px] bg-gray-500 mr-2"></div>
            <p class="font-bold text-orange-600 text-xl md:text-2xl">
              What we Do
            </p>
          </div>
          <p
            class="w-3/4 mx-auto md:mx-0 md:w-7/12 mt-4 text-gray-700 text-sm md:text-[18px] leading-[25px] md:mt-6"
          >
            Lorem ipsum dolor sit consetetur sadipscing sed diam nonumy eirmod
            tempor
          </p>
          <button
            class="mt-4 md:mt-8 bg-orange-600 px-8 py-3 rounded-full text-white font-semibold"
          >
            Contact Us
          </button>
        </div>
        <div class="md:w-1/2 mt-12 md:mt-0 mx-auto md:mx-0">
          <img
            :src="require('../../assets/imgs/bg.jpg')"
            alt=""
            style="z-index: -1"
            class="rounded-full md:w-[500px] w-[300px] sm:w-350 sm:h-[350px] h-[300px] md:h-[500px] object-cover absolute right-[50px] md:right-[250px] sm:right-[300px] z-2"
          />
          <div
            class="hidden md:flex flex-row justify-between z-4 h-full w-full"
          >
            <div class="ml-20 mt-20">
              <CommentComponent
                content="Lorem ipsum dolor sit amet, consetetur."
                mypic="user.png"
              />
            </div>
            <div class="mt-56 mr-16">
              <CommentComponent
								content="Lorem ipsum dolor sit amet, consetetur." 
                mypic="user.png"
              />
            </div>
          </div>
          <div class="hidden md:flex flex-col justify-between">
            <div class="ml-40 mt-12">
              <CommentComponent
                content="Lorem ipsum dolor sit amet, consetetur."
                mypic="user.png"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: 'MainComponent',
}
</script>
