<template>
  <div>
    <SubscriptionOption title="Basique" cost="150 000">
      <ul class="list-disc list-inside px-2">
        <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
        <li>Lorem Ipsum has been the industry's standard dummy text ever since the 1500s</li>
        <li>when an unknown printer took a galley of type and scrambled</li>
        <li>it to make a type specimen book. It has survived not only five centuries</li>
      </ul>
    </SubscriptionOption>
    <SubscriptionOption title="PRO" cost="200 000">
      <ul class="list-disc list-inside px-2">
        <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
        <li>Lorem Ipsum has been the industry's standard dummy text ever since the 1500s</li>
        <li>when an unknown printer took a galley of type and scrambled</li>
        <li>it to make a type specimen book. It has survived not only five centuries</li>
      </ul>
    </SubscriptionOption>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import SubscriptionOption from '~/components/shared/subscription-option.vue';

export default Vue.extend({
  components: { SubscriptionOption },
  layout: "client"
})
</script>
