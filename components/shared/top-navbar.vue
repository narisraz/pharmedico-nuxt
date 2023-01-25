
<template>
  <div>
    <div class="flex w-full items-center justify-between p-4">
      <MenuIcon />
      <div>Pharmedico</div>
      <UserIcon />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import MenuIcon from './icons/menu-icon.vue';
import UserIcon from './icons/user-icon.vue';

export default Vue.extend({
    components: { MenuIcon, UserIcon }
})
</script>
