<template>
  <div class="bg-black/5 h-screen">
    <TopNavbar />

    <div class="px-4">
      <div class="sticky top-2">
        <SearchForm />
      </div>

      <div class="flex justify-between my-2">
        <div>
          <span class="font-semibold">Rakoto</span> (28)
        </div>
        <div class="flex space-x-1">
          <FilterIcon />
          <div>
            Filtrer
          </div>
        </div>
      </div>

      <div class="space-y-2">
        <ResultDoctor />
        <ResultPharmacy />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import TopNavbar from '~/components/shared/top-navbar.vue';
import SearchForm from '~/components/shared/search-form.vue';
import FilterIcon from '~/components/shared/icons/filter-icon.vue';
import ResultDoctor from '~/components/search/result-doctor.vue';
import ResultPharmacy from '~/components/search/result-pharmacy.vue';

export default Vue.extend({
    components: { TopNavbar, SearchForm, FilterIcon, ResultDoctor, ResultPharmacy }
})
</script>
