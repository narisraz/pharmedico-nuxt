<template>
  <div class="rounded-md shadow-md bg-white">
    <div class="relative">
      <div class="uppercase rounded-t-md font-bold text-center bg-green-500 text-white p-8 tracking-wider w-full text-2xl">
        {{ title }}
      </div>
      <div class="absolute right-0 left-0 -bottom-5 text-center">
        <div class="flex justify-center">
          <div class="rounded-full bg-green-500 px-4 py-2 text-white font-semibold border-2 border-white shadow-md">
            {{ cost }} Ar
          </div>
        </div>
      </div>
    </div>
    <div class="p-2 m-4">
      <slot></slot>
      <div class="flex justify-center text-blue-500 m-2">
        <ThumbUp />
        <button type="button" class="bg-blue-500 rounded-lg px-3 py-2 text-white mt-4 shadow-md font-bold hidden">Choisir</button>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import ThumbUp from '~/components/shared/icons/thumb-up.vue';

defineProps({
  title: {
    required: true,
    type: String
  },
  cost: {
    required: true,
    type: String
  }
})
</script>
