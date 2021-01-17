<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" /> -->
    <HomeVue />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import HomeVue from "@/components/Home.vue";
@Component({
  components: {
    HelloWorld,
    HomeVue
  },
})
export default class Home extends Vue {}
</script>
