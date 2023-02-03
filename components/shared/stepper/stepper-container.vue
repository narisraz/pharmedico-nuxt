<template>
  <div class="space-y-5 h-full">
    <StepperHeader :number-of-steps="numberOfSteps" :titles="titles" />

    <slot></slot>

    <div class="flex space-x-2">
      <button :disabled="activeStep == 0" type="button" :class="`bg-white disabled:shadow-none disabled:text-gray-300 disabled:bg-slate-200 py-2 px-4 w-full rounded-md shadow-md uppercase text-green-500 font-semibold tracking-wide`" @click="goBack">Précédent</button>
      <button type="button" :class="`bg-green-500  py-2 px-4 w-full rounded-md shadow-md uppercase text-white font-semibold tracking-wide`" @click="goNext">
        {{ activeStep < numberOfSteps - 1 ? 'Suivant' : 'Valider' }}
      </button>
    </div>
  </div>
</template>

<script lang="ts" setup>
import { provide, ref } from 'vue';
import StepperHeader from './stepper-header.vue';

const props = defineProps({
  numberOfSteps: {
    required: true,
    type: Number
  },
  validate: {
    required: true,
    type: Function
  },
  activeStep: {
    required: true,
    type: Number
  },
  titles: {
    required: true,
    type: Array
  },
  updateCurrentIndex: {
    required: true,
    type: Function
  }
})

const currentIndex = ref(props.activeStep)

provide('current-step', currentIndex)

function goNext() {
  if (currentIndex.value < props.numberOfSteps - 1) {
    props.updateCurrentIndex(++currentIndex.value)
  } else {
    props.validate()
  }
}

function goBack() {
  props.updateCurrentIndex(--currentIndex.value)
}
</script>
