<template>
  <SearchResultsPage />
</template>

<script lang="ts">
import Vue from 'vue'
import SearchResultsPage from '~/components/search/search-results-page.vue';

export default Vue.extend({
    components: { SearchResultsPage },
    layout: "client"
})
</script>
