<template>
  <VisitorSignupPage />
</template>

<script lang="ts">
import Vue from 'vue'
import VisitorSignupPage from '~/components/visitors/visitor-signup-page.vue';

export default Vue.extend({
    components: { VisitorSignupPage },
    layout: "client"
})
</script>
