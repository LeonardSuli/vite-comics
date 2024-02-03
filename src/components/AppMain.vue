<script>

import AppIcon from './AppIcon.vue';

export default{
  name: 'AppMain',
  components: {
    AppIcon
  }
}
</script>


<template>

    <main>

      <div class="main_top">

        <div class="container">
          Content
        </div>

      </div>

      <AppIcon></AppIcon>

    </main>

</template>


<style scoped>

.main_top{
  background-color: var(--dc-dark);
  color: var(--dc-light);
  padding: 2rem 0;
}

</style>