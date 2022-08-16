<template>
  <div class="mt-4 z-10 flex items-center flex-col">
    <div class="bg-orange-600 p-4 rounded-full h-20 w-20 flex items-center">
      <img :src="require(`../../assets/imgs/${mypic}`)" class="w-14 h-14" />
    </div>
    <p
      class="text-gray-700 text-sm leading-[22px] mt-2 w-[150px] md:w-3/4 text-center"
    >
      {{ text }}
    </p>
  </div>
</template>
<script>
export default {
  name: 'FooterCardComponent',
  props: {
    text: {
      type: String,
    },
    mypic: {
      type: String,
    },
  },
}
</script>
