<script setup>
import { ref } from "vue";
import { useRoute } from "vue-router";

const route = useRoute();
</script>

<template>
  <!-- <h1>Product</h1> -->
  <h1>Product {{ route.params.name }}</h1>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem soluta,
    earum voluptate repellat molestiae aliquam aliquid voluptatem dolorem!
    Sapiente in voluptas sint laboriosam sequi at ipsum ea perferendis voluptate
    consequatur?
  </p>
</template>

<style scoped>
    .router-link-active .router-link-exact-active{
        color: blue;
        
    }
</style>>


