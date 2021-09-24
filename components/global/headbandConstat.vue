<template>
  <section class="w-full bg-full mt-10 py-6">
    <div class="section-wrapper text-white">
      <blockquote>
        <div class="flex flex-wrap">
          <div class="w-[41px]">
            <svg width="41" height="31" viewBox="0 0 41 31" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M12.4712 2.15039C6.19989 6.2484 1.77283 12.9643 1.77283 20.3631C1.77283 26.3963 5.70785 29.925 10.2578 29.925C14.5617 29.925 17.7589 26.7377 17.7589 22.9812C17.7589 19.2249 14.9306 16.4931 11.2416 16.4931C10.5038 16.4931 9.51999 16.6068 9.27397 16.7206C9.88889 12.8505 13.8239 8.29729 17.7592 6.02067L12.4712 2.15039ZM33.6222 2.15039C27.4735 6.2484 23.0467 12.9643 23.0467 20.3631C23.0467 26.3963 26.9817 29.925 31.5316 29.925C35.7127 29.925 39.0328 26.7377 39.0328 22.9812C39.0328 19.2249 36.0816 16.4931 32.3923 16.4931C31.6545 16.4931 30.7938 16.6068 30.5478 16.7206C31.1627 12.8505 34.9749 8.29729 38.9099 6.02067L33.6222 2.15039Z" stroke="white" stroke-width="2"/>
            </svg>
          </div>
          <div class="w-[80%] grid gap-y-4 pl-4">
            <p>
              <span class="block font-bold">Notre constat</span>
              Pour une productivité durable, les besoins de dialogue, de lien social et de culture sont très forts.
              <span class="block">
               Pourtant, vos collaborateurs sont en télétravail la majorité du temps ou en déplacement, ils n’ont plus l’occasion d’échanger, si ce n’est par mail, téléphone ou visioconférence, ou ne se sont même jamais rencontrés (ex : nouveaux arrivants).
            </span>
            </p>
            <p>
              <span class="block font-bold">Notre conclusion</span>
              Pour assurer vos performances, la période actuelle est une opportunité pour votre entreprise d’innover en termes d’échanges et de dialogue social.
            </p>
            <p>
              <span class="block font-bold">Notre proposition : </span>
              Innover en s’appuyant sur l’intelligence collective de vos collaborateurs et la Musique.
            </p>
          </div>
        </div>

      </blockquote>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeadbandConstat'
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
