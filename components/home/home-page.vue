<template>
  <div class="bg-black/5">
    <TopNavbar />

    <div class="px-4">
      <div>Rechercher les meilleurs <span class="text-green-400 font-semibold">médecins</span>
        et <span class="text-green-400 font-semibold">pharmacies</span> dans votre région</div>

      <SearchForm />
      <PopularDoctors class="mt-2" />
      <PopularPharmacies class="mt-2" />

    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import TopNavbar from '~/components/shared/top-navbar.vue';
import SearchForm from '~/components/home/search-form.vue';
import PopularDoctors from '~/components/home/popular-doctors.vue';
import PopularPharmacies from '~/components/home/popular-pharmacies.vue';

export default Vue.extend({
    components: { TopNavbar, SearchForm, PopularDoctors, PopularPharmacies }
})
</script>
