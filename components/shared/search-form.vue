<template>
  <form>
    <div class="relative">
      <button class="absolute inset-y-0 px-2 items-center">
        <SearchIcon />
      </button>

      <input type="text" class="w-full border p-2 pl-10 rounded-md shadow-md focus:outline-0 focus:shadow-green-200" placeholder="Rechercher...">
    </div>
  </form>
</template>

<script lang="ts">
import Vue from 'vue'
import SearchIcon from '~/components/shared/icons/search-icon.vue';

export default Vue.extend({
    components: { SearchIcon }
})
</script>
