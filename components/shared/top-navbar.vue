
<template>
  <div>
    <div class="flex w-full items-center justify-between p-4">
      <MenuIcon />
      <div>Pharmedico</div>
      <div class="flex space-x-2">
        <button>
          <SearchIcon />
        </button>
        <UserIcon />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import MenuIcon from './icons/menu-icon.vue';
import SearchIcon from './icons/search-icon.vue';
import UserIcon from './icons/user-icon.vue';

export default Vue.extend({
    components: { MenuIcon, UserIcon, SearchIcon }
})
</script>
