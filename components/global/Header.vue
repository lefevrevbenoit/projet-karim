<template>
  <div>
    <header class="section-header relative">
      <nav class="flex flex-wrap justify-between">
        <div>
          logo
        </div>
        <ul>
          <li class="hidden flex">
            <a href="#">
              A propos de
            </a>
            <a href="#">
              Activités / services
            </a>
          </li>
          <li>
            <a href="#">
              Contact
            </a>
          </li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="postcss" scoped>
.section-header {
  background: url("~/assets/images/bg-hero-section-xl.jpg") no-repeat;
  @apply bg-cover w-full h-full min-h-[300px];
  background-position: 64%;
}
</style>
