<template>
  <div>
    <div class="flex space-x-1 bg-white rounded-md shadow-md">
      <img class="w-40 object-cover" src="https://f.hellowork.com/obs-static-images/seo/ObsJob/medecin-generaliste.jpg" />
      <div class="my-2">
        <div class="font-semibold">Razafimahatratra Naris Noël</div>
        <div class="flex space-x-1 text-sm items-center">
          <LocationIcon class="h-4 font-light" />
          <div class="font-light">Sabotsy Namehana</div>
        </div>
        <div class="flex space-x-1 text-sm items-center">
          <FireIcon class="h-4 font-light" />
          <div class="font-light">Chirurgien</div>
        </div>
        <RatingStars class="my-2" />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import LocationIcon from '~/components/shared/icons/location-icon.vue';
import FireIcon from '~/components/shared/icons/fire-icon.vue';
import RatingStars from '~/components/shared/rating-stars.vue';

export default Vue.extend({
    components: { LocationIcon, FireIcon, RatingStars }
})
</script>
