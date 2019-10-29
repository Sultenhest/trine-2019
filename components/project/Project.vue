<template>
  <div class="project__container md:h-screen md:my-0">
    <img class="project__image" :src="imageSrc" />
  </div>
</template>

<script>
export default {
  name: 'Project',
  props: {
    imageSrc: String
  }
}
</script>

<style lang="scss">
.project__container {
  @apply .flex .justify-center .items-center;

  .project__image {
    @apply .shadow;
    max-height: 80vh;
  }
}
</style>
