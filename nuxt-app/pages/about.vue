<script setup lang="ts">
const route = useRoute()
</script>

<template>
  <!-- <p>Current route: {{ route.path }}</p> -->
  <div class="max-w-full">
    <GlobalHeader />
    <div class="flex justify-center">
      <div class="card w-96 bg-base-100 shadow-xl">
        <figure><img src="https://daisyui.com/images/stock/photo-1606107557195-0e29a4b5b4aa.jpg" alt="Shoes" /></figure>
        <div class="card-body">
          <h2 class="card-title">Dog!!!!</h2>
          <p>If a dog chews shoses whose shoes does he choose?</p>
          <div class="card-actions justify-end">
            <button class="btn btn-primary">Buy Now</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
