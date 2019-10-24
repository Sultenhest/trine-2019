<template>
  <div class="project__container md:h-screen md:my-0">
    <img class="project__image" src="https://source.unsplash.com/random/1000x800" />
  </div>
</template>

<script>
export default {
  name: 'Project'
}
</script>

<style lang="scss">
.project__container {
  @apply .mx-4 .my-4 .flex .justify-center .items-center;

  .project__image {
    @apply .shadow;
    max-height: 80vh;
  }
}
</style>
