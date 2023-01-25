<template>
  <div class="w-44 p-2 shadow-md rounded-md bg-white">
    <div class="flex justify-center">
      <img src="http://www.pharmaciedugrandjardin.com/wp-content/uploads/2011/03/Photo-Fa%C3%A7ade-36.jpg" class="h-40 object-fill" />
    </div>
    <div class="font-semibold">Pharmacie s. Namehana</div>
    <div class="flex space-x-1 text-sm items-center">
      <LocationIcon />
      <div class="font-light">Sabotsy Namehana</div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import LocationIcon from '../shared/icons/location-icon.vue';

export default Vue.extend({
    components: { LocationIcon }
})
</script>
