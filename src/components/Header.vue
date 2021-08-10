<script>
import UserDisplay from "./UserDisplay.vue"

export default {
  name: 'Header',
  components:{
    UserDisplay
  }
}
</script>

<template>
  <header>
    <nav>
      <a href="#">Retourner à Doc9bonus</a>
    </nav>
    <UserDisplay/>
  </header>
</template>

<style lang="scss" scoped>

  header {
    width: calc(100% - 4em);
    padding: 1em 2em;
    display: flex;
    justify-content: space-between;
    border-bottom: 1px solid lightgrey;
  }

</style>