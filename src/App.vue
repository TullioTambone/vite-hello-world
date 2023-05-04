<script>
  import MyTitle from './components/MyTitle.vue';
  import AppHero from './components/AppHero.vue';
  // import { defineAsyncComponent } from "vue";

  export default{
        name: "App",
        components: {
          MyTitle,
          AppHero,

            // HelloWorld: defineAsyncComponent(() =>
            // import("./components/myTitle.vue")),

        }
    }
</script>

<template>
  <div>
    <AppHero/>
    <MyTitle/>
  </div>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
