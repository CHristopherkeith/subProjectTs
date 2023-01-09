<template>
  <div class="home">
    <h1>HomeView7 page from this {{ title }}</h1>
    <div>-------------------------------------------------------------------</div>
    <HomeView/>
  </div>
  
</template>

<script lang="ts" setup>
import { Ref, ref } from "setupDemo/node_modules/vue";
// import HomeView from "@/views/HomeView/HomeView.vue";
import HomeView from "setupDemo/src/views/HomeView/HomeView.vue";

const title: Ref<string> = ref("");

title.value = "subProjectTs";
</script>
