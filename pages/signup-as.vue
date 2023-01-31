<template>
  <SignupAsPage />
</template>

<script lang="ts">
import Vue from 'vue'
import SignupAsPage from '~/components/auth/signup-as-page.vue';

export default Vue.extend({
    components: { SignupAsPage },
    layout: "client"
})
</script>
