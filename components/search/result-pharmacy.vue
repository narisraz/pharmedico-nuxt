<template>
  <div>
    <div class="flex space-x-2 bg-white rounded-md shadow-md">
      <img class="w-40 object-cover" src="http://www.pharmaciedugrandjardin.com/wp-content/uploads/2011/03/Photo-Fa%C3%A7ade-36.jpg" />
      <div class="my-2">
        <div class="font-semibold">Pharmacie s. Namehana</div>
        <div class="flex space-x-1 text-sm items-center">
          <LocationIcon />
          <div class="font-light">Sabotsy Namehana</div>
        </div>
        <RatingStars class="my-2" />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import LocationIcon from '~/components/shared/icons/location-icon.vue';
import RatingStars from '~/components/shared/rating-stars.vue';

export default Vue.extend({
    components: { LocationIcon, RatingStars }
})
</script>
