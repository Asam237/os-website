<template>
  <header class="px-4 py-6 border-b-2">
    <div class="container mx-auto flex justify-between items-center md:px-20">
      <h1 class="text-xl md:text-2xl" style="font-family: 'Pacifico', cursive">
        OS <span class="text-orange-600 w-3 h-3">.</span>
      </h1>
      <nav class="hidden md:flex">
        <ul v-for="(item, myIndex) in navs" :key="myIndex">
          <li
            class="mr-8 text-gray-800 font-normal text-sm md:text-[18px] leading-[25px]"
          >
            <a class="text-base hover:underline uppercase" :href="item.link">{{
              item.name
            }}</a>
          </li>
        </ul>
      </nav>
      <div
        class="border-2 border-none text-white bg-orange-600 px-4 py-2 rounded-full font-semibold"
      >
        <a href="mailto:mail@test.cm"> Join Community </a>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'HeaderComponent',
  data() {
    return {
      navs: [
        {
          name: 'Home',
          link: '#',
        },
        {
          name: 'Pricing',
          link: '#',
        },
        {
          name: 'Testimial',
          link: '#',
        },
        {
          name: 'FAQ',
          link: '#',
        },
      ],
    }
  },
}
</script>
