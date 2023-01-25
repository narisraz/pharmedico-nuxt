<template>
  <div>
    <div class="pb-1">
      <div class="flex justify-between">
        <div>
          <span class="font-semibold">Médecins</span> populaires à Antananarivo
        </div>
        <a href="#" class="text-blue-600 font-semibold">Voir plus</a>
      </div>
    </div>

    <div class="flex pb-2 space-x-2 overflow-scroll">
      <PopularDoctorCard />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import PopularDoctorCard from '~/components/home/popular-doctor-card.vue';

export default Vue.extend({
    components: { PopularDoctorCard }
})
</script>
