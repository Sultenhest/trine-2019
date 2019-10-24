<template>
  <nav class="nav__container md:fixed md:h-screen md:w-24">
    <div class="nav__inner">
      <div class="nav__links">
        <nuxt-link class="nav__link" to="/">Home</nuxt-link>
        <nuxt-link class="nav__link" to="/info">Info</nuxt-link>
      </div>
    </div>

    <div class="nav__logo top-0 bottom-auto md:top-auto md:bottom-0">
      <nuxt-link class="nav__link" to="/">Logo</nuxt-link>
    </div>
  </nav>
</template>

<style lang="scss">
.nav__container {
  @apply .top-0 .right-0;

  .nav__inner {
    @apply .h-24;
    max-width: 100vh;
    width: 100vh;
    @media (min-width: 768px) {
      transform: rotate(90deg) translateY(-100%);
      transform-origin: 0 0;
    }

    .nav__links {
      @apply .flex .flex-no-wrap .h-full .ml-12;

      .nav__link {
        @apply .my-auto .mr-6;
      }
    }
  }

  .nav__logo {
    @apply .fixed .right-0 .w-24 .h-24 .flex .justify-center .items-center;
  }
}
</style>
