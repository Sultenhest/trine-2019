<template>
  <div class="projectlist__container">
    <VueLoop>
      <Project class="item" imageSrc="/img/1.jpeg" />
      <Project class="item" imageSrc="/img/2.jpeg" />
      <Project class="item" imageSrc="/img/3.jpeg" />
    </VueLoop>
  </div>
</template>

<script>
import VueLoop from '~/components/utilities/VueLoop.vue'
import Project from '~/components/project/Project.vue'

export default {
  components: {
    VueLoop,
    Project
  }
}
</script>

<style lang="scss">
.projectlist__container{
  @apply .z-0;
}
</style>
