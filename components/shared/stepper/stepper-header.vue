<template>
  <div class="flex space-x-2">
    <div class="bg-green-500 text-white rounded p-1 font-bold items-center flex">
      {{ currentStep + 1 }}/{{ numberOfSteps }}
    </div>
    <div class="w-full space-y-1">
      <div class="h-2 w-full bg-white rounded-md">
        <div class="h-2 bg-green-500 rounded-md transition-all ease-in duration-200" :style="`width: ${(currentStep / (props.numberOfSteps - 1)) * 100}%`"></div>
      </div>
      <div class="font-semibold uppercase">
        {{ titles[currentStep] }}
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { inject } from 'vue';

const props = defineProps({
  numberOfSteps: {
    required: true,
    type: Number
  },
  titles: {
    required: true,
    type: Array
  }
})

const currentStep = inject('current-step', 0)
</script>
