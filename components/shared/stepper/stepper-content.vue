<template>
  <div :class="{'hidden': currentStep !== props.step}">
    <slot></slot>
  </div>
</template>

<script lang="ts" setup>import { inject } from 'vue';

const props = defineProps({
  step: {
    required: true,
    type: Number
  }
})

const currentStep = inject('current-step', 0)
</script>
