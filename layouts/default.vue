<template>
  <div>
    <Header />
    <div class="section-wrapper absolute left-0 right-0 top-[170px]">
      <Intro />
      <Apropos />
      <HeadbandTextRSE />
      <Services />
      <HeadbandConstat />
    </div>
  </div>
</template>


<style lang="scss">
html {
  @apply sm:overflow-x-hidden;
}
body {
  @apply font-inter text-base text-color-body sm:overflow-x-hidden;
}
.section-wrapper {
  @apply px-4 w-full max-w-screen-xl mx-auto xl:px-6;
}
</style>
<script>

</script>