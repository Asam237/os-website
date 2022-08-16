<template>
  <div style="margin: 0; padding: 0">
    <HeaderComponent />
    <MainComponent />
    <FooterComponent />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  head: {
    title: "Orthez Service  |  Page d'accueil",
    link: [
      {
        rel: 'stylesheet',
        href: 'https://fonts.googleapis.com/css2?family=Pacifico&display=swap',
      },
    ],
  },
}
</script>
