<template>
  <form class="mx-4">
    <StepperContainer
      :active-step="activeStep"
      :number-of-steps="titles.length"
      :validate="validate"
      :titles="titles"
      :update-current-index="updateCurrentIndex"
    >
      <StepperContent :step="0">
        <Step1 />
      </StepperContent>

      <StepperContent :step="1">
        <Step2 />
      </StepperContent>

      <StepperContent :step="2">
        <Step3 />
      </StepperContent>

      <StepperContent :step="3">
        <Step4 />
      </StepperContent>

      <StepperContent :step="4">
        <Step5 />
      </StepperContent>
    </StepperContainer>
  </form>
</template>

<script lang="ts" setup>
import { ref } from 'vue';
import Step1 from './step-1.vue';
import Step2 from './step-2.vue';
import Step3 from './step-3.vue';
import Step4 from './step-4.vue';
import Step5 from './step-5.vue';
import StepperContainer from '~/components/shared/stepper/stepper-container.vue';
import StepperContent from '~/components/shared/stepper/stepper-content.vue';

const titles = [
        'Informations personnelles',
        'Informations légales',
        'Contact et adresses',
        'Informations de connexions',
        'Plan d\'abonnement'
      ]
const activeStep = ref(4)

function updateCurrentIndex(value: number) {
  activeStep.value = value
}

function validate() {
}
</script>
