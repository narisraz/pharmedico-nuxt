<template>
  <DoctorPage />
</template>

<script lang="ts">
import Vue from 'vue'
import DoctorPage from '~/components/practitioners/doctors/doctor-page.vue';

export default Vue.extend({
    components: { DoctorPage },
    layout: "client"
})
</script>
