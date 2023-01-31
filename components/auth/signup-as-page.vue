<template>
  <div class="px-4 space-y-2">
    <h1 class="font-extrabold tracking-wide text-xl">Choisissez le type de votre compte</h1>
    <button class="flex shadow-md p-2 space-x-2 rounded-md focus:bg-green-400 focus:text-white focus:shadow-emerald-300">
      <div>
        <UserIcon />
      </div>
      <div class="text-left">
        <h2 class="font-bold">Visiteur</h2>
        <p class="text-sm">Vous pourrez commenter ou noter les personnes ou établissement que vous aimez</p>
      </div>
    </button>
    <button class="flex shadow-md p-2 space-x-2 rounded-md focus:bg-green-400 focus:text-white focus:shadow-emerald-300">
      <div>
        <DoctorIcon />
      </div>
      <div class="text-left">
        <h2 class="font-bold">Médecin</h2>
        <p class="text-sm">Faites vous retrouver facilement par vos futures clients</p>
      </div>
    </button>
    <button class="flex shadow-md p-2 space-x-2 rounded-md focus:bg-green-400 focus:text-white focus:shadow-emerald-300">
      <div>
        <PharmacyIcon />
      </div>
      <div class="text-left">
        <h2 class="font-bold">Pharmacie</h2>
        <p class="text-sm">Faites vous retrouver facilement par vos futures clients</p>
      </div>
    </button>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import UserIcon from '~/components/shared//icons/user-icon.vue';
import DoctorIcon from '~/components/shared//icons/doctor-icon.vue';
import PharmacyIcon from '~/components/shared//icons/pharmacy-icon.vue';

export default Vue.extend({
    components: { UserIcon, DoctorIcon, PharmacyIcon },
})
</script>
