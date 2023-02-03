<template>
  <div class="space-y-5">
    <div class="flex flex-col w-full">
      <label for="email" class="font-semibold">Email</label>
      <div class="relative">
        <div class="absolute left-4 top-1/2 transform -translate-x-1/2 -translate-y-1/2 text-black/25">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 6a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0zM4.501 20.118a7.5 7.5 0 0114.998 0A17.933 17.933 0 0112 21.75c-2.676 0-5.216-.584-7.499-1.632z" />
          </svg>
        </div>
        <input id="email" type="text" name="email" placeholder="Entrez votre adresse email" class="border-b-2 pl-8 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
      </div>
    </div>
    <div class="flex flex-col w-full">
      <label for="password" class="font-semibold">Mot de passe</label>
      <div class="relative">
        <div class="absolute left-4 top-1/2 transform -translate-x-1/2 -translate-y-1/2 text-black/25">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
            <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 10.5V6.75a4.5 4.5 0 10-9 0v3.75m-.75 11.25h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H6.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z" />
          </svg>
        </div>
        <input id="password" type="password" name="email" placeholder="Entrez votre mot de passe" class="border-b-2 pl-8 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
      </div>
    </div>
    <div class="flex flex-col w-full">
      <label for="confirmation" class="font-semibold">Confirmation</label>
      <div class="relative">
        <div class="absolute left-4 top-1/2 transform -translate-x-1/2 -translate-y-1/2 text-black/25">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
            <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 10.5V6.75a4.5 4.5 0 10-9 0v3.75m-.75 11.25h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H6.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z" />
          </svg>
        </div>
        <input id="confirmation" type="password" name="email" placeholder="Confirmez votre mot de passe" class="border-b-2 pl-8 py-2 mt-1 w-full focus:outline-0 focus:border-green-500" />
      </div>
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
