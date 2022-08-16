<template>
  <div
		class="shadow-2xl bg-white px-4 py-1 rounded-full w-[210px] flex items-center"
		style="opacity: 0.9"
  >
    <img :src="require(`../../assets/imgs/${mypic}`)" class="w-10 h-10 rounded-full" />
    <p class="text-sm ml-2">
      {{ content }}
    </p>
  </div>
</template>
<script>
export default {
  name: 'CommentComponent',
  props: {
    mypic: {
      type: String,
    },
    content: {
      type: String,
    },
  },
}
</script>
