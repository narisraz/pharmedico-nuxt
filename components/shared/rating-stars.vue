<template>
  <div class="flex space-x-1">
    <div class="flex">
      <StarSolidIcon />
      <StarSolidIcon />
      <StarSolidIcon />
      <StarSolidIcon />
      <StarSolidIcon />
    </div>
    <div>4.8</div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import StarSolidIcon from './icons/star-solid-icon.vue';

export default Vue.extend({
    components: { StarSolidIcon }
})
</script>
