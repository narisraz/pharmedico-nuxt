<template>
  <div class="px-4">
    <div>Rechercher les meilleurs <span class="text-green-400 font-semibold">médecins</span>
      et <span class="text-green-400 font-semibold">pharmacies</span> dans votre région</div>

    <div class="sticky top-2 my-2">
      <SearchForm />
    </div>
    <PopularDoctors class="mt-2" />
    <PopularPharmacies class="mt-2" />

  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import PopularDoctors from '~/components/home/popular-doctors.vue';
import PopularPharmacies from '~/components/home/popular-pharmacies.vue';
import SearchForm from '~/components/shared/search-form.vue';

export default Vue.extend({
    components: { PopularDoctors, PopularPharmacies, SearchForm }
})
</script>
