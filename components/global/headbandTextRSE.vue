<template>
  <section class="w-full bg-full mt-10 py-6">
    <div class="section-wrapper text-white">
      <h2 class="text-[22px] font-bold mb-4">Pourquoi s’intéresser à la RSE ?</h2>
      <blockquote class="border-l-[4px]">
        <div class="grid gap-y-4 pl-4">
          <p>
            Dans un monde où règnent l’incertitude et l’accélération du changement, les entreprises et les organisations
            sont soumises à des contraintes fortes de leurs parties prenantes (exigences réglementaires, modification rapide
            des attentes de la société, vitesse et transmission de l’information, mondialisation).
          </p>
          <p>
            Outre leur performance économique, elles se doivent de maîtriser l’impact de leurs activités sur l’environnement
            et sur leur sphère d’influence sociale (interne) et sociétale (externe). A défaut, la profitabilité, voire
            l’existence de leur activité peut être impactée.
          </p>
          <p>
            In fine, cette analyse permettra de proposer une stratégie personnalisée et innovante à forte valeur ajoutée
            pour l’entreprise, tant sur le plan de son image (attractivité), que de ses capacités de résilience, et de
            maintien voire d’augmentation de son profit.
          </p>
        </div>
      </blockquote>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeadbandTextRSE'
}
</script>

<style lang="scss" scoped>
  .bg-full {
    @apply relative;
    &:after {
      content: "";
      @apply absolute w-screen h-full top-0 left-1/2 transform -translate-x-1/2 z-[-10] bg-gray-900;
    }
  }
</style>
