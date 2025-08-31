<script setup>
import BaseButton from '@/components/BaseButton/BaseButton.vue'
</script>

<template>
  <main class="flex h-screen">
    <section class="flex flex-1 justify-center items-center px-5 bg-primary">
      <div class="text-white text-center">
        <img class="inline mb-6" src="./assets/image/map-pin.svg" alt="map icon" />
        <h1 class="font-bold text-4xl mb-7">IT traveler</h1>
        <p class="leading-6 mb-11">
          Простий і зручний веб додаток, який дозволить тобі відмічати твої улюблені місця, а також
          ті, в яких би ти дуже хотів побувати. Тож не зволікай і спробуй сам.
        </p>
        <BaseButton></BaseButton>
      </div>
    </section>
    <section class="flex-1">
      <img
        class="h-full w-full object-cover"
        src="./assets/image/static-map.png"
        alt="static map image"
      />
    </section>
  </main>
</template>
