<template>
  <div class="w-44 p-2 shadow-md rounded-md bg-white">
    <div class="flex justify-center">
      <img src="https://www.collinsdictionary.com/images/full/surgeon_214772131.jpg" class="h-40 object-fill" />
    </div>
    <div class="font-semibold">Razafimahatratra Naris</div>
    <div class="flex space-x-1 text-sm items-center">
      <LocationIcon class="h-4 font-light" />
      <div class="font-light">Sabotsy Namehana</div>
    </div>
    <div class="flex space-x-1 text-sm items-center">
      <FireIcon class="h-4 font-light" />
      <div class="font-light">Chirurgien</div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import FireIcon from '~/components/shared/icons/fire-icon.vue';
import LocationIcon from '~/components/shared/icons/location-icon.vue';

export default Vue.extend({
    components: { FireIcon, LocationIcon }
})
</script>
