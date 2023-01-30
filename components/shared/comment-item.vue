<template>
  <div class="bg-white p-2 my-1 w-full">
    <RatingStars />
    <div class="pt-1">
      <span class="text-blue-500">Naris</span><span class="text-sm"> - 23/12/2022</span>
    </div>
    <p>
      "Très bon médecin"
    </p>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import RatingStars from '~/components/shared/rating-stars.vue';

export default Vue.extend({
    components: { RatingStars }
})
</script>
