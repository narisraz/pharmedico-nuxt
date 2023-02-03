<template>
  <div class="space-y-5">
    <div class="flex flex-col w-full">
      <label for="tel" class="font-semibold">Tel</label>
      <input id="tel" type="text" name="name" placeholder="Entrez votre numéro de téléphone" class="border-b-2 pl-3 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
    </div>
    <div class="flex flex-col w-full">
      <label for="region" class="font-semibold">Région</label>
      <input id="region" type="text" name="region" placeholder="Entrez votre région" class="border-b-2 pl-3 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
    </div>
    <div class="flex flex-col w-full">
      <label for="district" class="font-semibold">District</label>
      <input id="district" type="text" name="district" placeholder="Entrez votre district" class="border-b-2 pl-3 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
    </div>
    <div class="flex flex-col w-full">
      <label for="commune" class="font-semibold">Commune</label>
      <input id="commune" type="text" name="commune" placeholder="Entrez votre commune" class="border-b-2 pl-3 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
    </div>
    <div class="flex flex-col w-full">
      <label for="lot" class="font-semibold">Lot</label>
      <input id="lot" type="text" name="lot" placeholder="Entrez votre adresse" class="border-b-2 pl-3 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
    </div>
    <div class="flex flex-col w-full">
      <label for="longitude" class="font-semibold">Longitude</label>
      <input id="longitude" type="text" name="lot" placeholder="Entrez votre adresse" class="border-b-2 pl-3 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
    </div>
    <div class="flex flex-col w-full">
      <label for="latitude" class="font-semibold">Latitude</label>
      <input id="latitude" type="text" name="lot" placeholder="Entrez votre adresse" class="border-b-2 pl-3 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
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
