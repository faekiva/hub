<script setup lang="ts">
const route = useRoute()

const posts = ref(["", ""])
</script>

<template>
  <!-- <p>Current route: {{ route.path }}</p> -->
  <GlobalHeader />
  <p class="flex justify-center w-full">{{ posts }}</p>
  <div class="flex justify-center w-full flex-wrap">

    <div class="flex flex-wrap justify-center stats bg-primary w-1/2 text-primary-content">
      <textarea v-for="(_, index) in posts" v-model="posts[index]"
        class="flex flex-wrap justify-center textarea textarea-ghost w-full" placeholder="Bio"></textarea>
    </div>
  </div>
</template>
