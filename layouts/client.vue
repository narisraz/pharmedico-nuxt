<template>
  <div>
    <TopNavbar />
    <Nuxt />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import TopNavbar from '~/components/shared/top-navbar.vue';

export default Vue.extend({
    components: { TopNavbar }
})
</script>
