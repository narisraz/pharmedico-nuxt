<template>
  <PharmacyPage />
</template>

<script lang="ts">
import Vue from 'vue'
import PharmacyPage from '~/components/institutions/pharmacy-page.vue';

export default Vue.extend({
    components: { PharmacyPage },
    layout: "client"
})
</script>
