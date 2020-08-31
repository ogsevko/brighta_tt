<template>
  <main class="main">
    <UserType />
  </main>
</template>

<script>
import UserType from './UserType';

export default {
  name: "Main",
  components: {
    UserType,
  }
}
</script>

<style scoped lang="scss">
.main {
  position: relative;
}
</style>
