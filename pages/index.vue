<template>
  <HomePage />
</template>

<script lang="ts">
import Vue from 'vue'
import HomePage from '~/components/home/home-page.vue';

export default Vue.extend({
    name: "IndexPage",
    components: { HomePage }
})
</script>
