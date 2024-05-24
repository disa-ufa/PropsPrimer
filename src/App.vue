<script setup>
import OptionsAPI from "./components/OptionsAPI.vue";
import CompositionAPI from "./components/CompositionAPI.vue";
import SviazPrimer from "./components/SviazPrimer.vue";
import PropsPrimer from "./components/PropsPrimer.vue"
</script>

<template>
 <PropsPrimer title="Кросовки 15" :price="9000">
  <button>Добавить</button>
</PropsPrimer>
 <PropsPrimer/>
 <PropsPrimer/>
</template>

<style scoped>

</style>
