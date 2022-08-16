<template>
  <footer
    data-aos="slide-up"
    class="px-4 md:px-0 pt-[300px] md:pt-56 pb-8 md:pb-12"
  >
    <div class="mx-auto container md:px-12">
      <div class="flex flex-col md:flex-row">
        <div class="hidden w-full md:w-3/12 md:flex flex-rows items-center">
          <img :src="logo" class="w-24 h-24 rounded-full object-cover" alt="" />
          <div class="ml-4 flex flex-col">
            <h1
              class="text-xl md:text-2xl"
              style="font-family: 'Pacifico', cursive"
            >
              Orthez<br />Services
            </h1>
            <a
              class="text-gray-700 text-sm leading-[22px] text-center font-semibold"
              href="tel:678 98 98 98"
              >(+229) 678 87 78 98</a
            >
          </div>
        </div>
        <div class="hidden md:flex w-[1px] bg-gray-300 mx-10" />
        <div class="w-full md:w-2/12 mt-4 md:mt-0">
          <FooterCardComponent
            text="rem ipsum dolor sit amet, consetetur."
            mypic="rabbit.png"
            mycolor="red-900"
          />
        </div>
        <div class="hidden md:flex w-[1px] bg-gray-300 mx-10" />
        <div class="w-full md:w-2/12 mt-4 md:mt-0">
          <FooterCardComponent
            text="rem ipsum dolor sit amet, consetetur."
            mypic="pig.png"
            mycolor="red-900"
          />
        </div>
        <div class="hidden md:flex w-[1px] bg-gray-300 mx-10" />
        <div class="w-full md:w-2/12 mt-4 md:mt-0">
          <FooterCardComponent
            text="rem ipsum dolor sit amet, consetetur."
            mypic="egg.png"
            mycolor="red-900"
          />
        </div>
      </div>
      <a href="tel:678 98 98 98" class="flex md:hidden justify-center mt-4">
        <FooterCardComponent
          text="(+229) 678 87 78 98"
          mypic="call.png"
          mycolor="red-900"
        />
      </a>
    </div>
  </footer>
</template>
<script>
export default {
  name: 'FooterComponent',
  data() {
    return {
      logo: require('../../assets/imgs/logo.jpg'),
    }
  },
}
</script>
