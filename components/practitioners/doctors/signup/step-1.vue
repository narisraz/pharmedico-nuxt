<template>
  <div class="space-y-5">
    <div class="flex flex-col w-full">
      <label for="name" class="font-semibold">Nom</label>
      <input id="name" type="text" name="name" placeholder="Entrez votre nom" class="border-b-2 pl-3 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
    </div>
    <div class="flex flex-col w-full">
      <label for="first-name" class="font-semibold">Prénom</label>
      <input id="first-name" type="text" name="name" placeholder="Entrez votre prénom" class="border-b-2 pl-3 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  components: {  },
  layout: "client"
})
</script>
