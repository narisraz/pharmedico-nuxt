<template>
  <SignupPage />
</template>

<script lang="ts">
import Vue from 'vue'
import SignupPage from '~/components/practitioners/doctors/signup/signup-page.vue';

export default Vue.extend({
    components: { SignupPage },
    layout: "client"
})
</script>
