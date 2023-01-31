<template>
  <LoginPage />
</template>

<script lang="ts">
import Vue from 'vue'
import LoginPage from '~/components/auth/login-page.vue';

export default Vue.extend({
    components: { LoginPage }
})
</script>
