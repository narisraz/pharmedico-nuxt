<template>
  <div>
    <TopNavbar />

    <div class="mx-4">
      <img class="h-60 object-cover rounded-lg shadow-md" src="https://f.hellowork.com/obs-static-images/seo/ObsJob/medecin-generaliste.jpg" />

      <div class="flex my-4 justify-between">
        <div>
          <div class="font-semibold">
            Dr Razafimahatratra Naris
          </div>
          <div class="text-sm">
            Médecin généraliste
          </div>
          <div class="mt-1">
            <RatingStars />
            <a href="#" class="text-sm text-blue-500">Voir les commentaires</a>
          </div>
        </div>
        <button class="text-red-600 h-fit shadow-md p-2 rounded-full">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
            <path fill-rule="evenodd" d="M1.5 4.5a3 3 0 013-3h1.372c.86 0 1.61.586 1.819 1.42l1.105 4.423a1.875 1.875 0 01-.694 1.955l-1.293.97c-.135.101-.164.249-.126.352a11.285 11.285 0 006.697 6.697c.103.038.25.009.352-.126l.97-1.293a1.875 1.875 0 011.955-.694l4.423 1.105c.834.209 1.42.959 1.42 1.82V19.5a3 3 0 01-3 3h-2.25C8.552 22.5 1.5 15.448 1.5 6.75V4.5z" clip-rule="evenodd" />
          </svg>
        </button>
      </div>

      <div>
        <h1 class="text-green-400 font-semibold uppercase">A propos</h1>
        <p class="font-light">
          Le lorem ipsum est, en imprimerie, une suite de mots sans signification utilisée à titre provisoire pour calibrer une mise en page, le texte définitif venant remplacer le faux-texte dès qu'il est prêt ou que la mise en page est achevée.
        </p>
      </div>

      <div class="mt-4">
        <h1 class="text-green-400 font-semibold uppercase">Contacts et adresse</h1>
        <p class="font-light">
          <div>
            <label class="font-semibold">Tel : </label>032 63 498 64
          </div>
          <div>
            <label class="font-semibold">Adresse : </label>Lot B 55 Sabotsy Namehana - Antananarivo - Avaradrano
          </div>
          <div>
            <img src="http://1.bp.blogspot.com/-lrhucjUiWjM/VPXaVmACubI/AAAAAAAADKU/_cmmIrJv3X0/s1600/doctor%2Bon%2Bdemand.png" alt="">
          </div>
        </p>
      </div>

      <div class="mt-4">
        <h1 class="text-green-400 font-semibold uppercase">Commentaires</h1>
        <div>
          <div class="bg-white p-2 my-2 w-full">
            <RatingStars />
            <div class="pt-1">
              <span class="text-blue-500">Naris</span><span class="text-sm"> - 23/12/2022</span>
            </div>
            <p>
              "Très bon médecin"
            </p>
          </div><div class="bg-white p-2 my-1 w-full">
            <RatingStars />
            <div class="pt-1">
              <span class="text-blue-500">Naris</span><span class="text-sm"> - 23/12/2022</span>
            </div>
            <p>
              "Accueil parfait"
            </p>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import RatingStars from '~/components/shared/rating-stars.vue';
import TopNavbar from '~/components/shared/top-navbar.vue';

export default Vue.extend({
    components: { TopNavbar, RatingStars }
})
</script>
