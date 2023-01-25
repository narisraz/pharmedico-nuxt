<template>
  <div>
    <div class="pb-1">
      <div class="flex justify-between">
        <div>
          <span class="font-semibold">Pharmacies</span> populaires à Antananarivo
        </div>
        <a href="#" class="text-blue-600 font-semibold">Voir plus</a>
      </div>
    </div>

    <div class="flex pb-2 space-x-2 overflow-scroll">
      <PopularPharmacyCard />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import PopularPharmacyCard from './popular-pharmacy-card.vue';

export default Vue.extend({
    components: { PopularPharmacyCard }
})
</script>
