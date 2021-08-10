<template>
  <section>
    <Header />
    <LoginModal />
  </section>
</template>

<script>
import Header from '@/components/Header.vue'
import LoginModal from '@/components/LoginModal.vue'

export default {
  name: 'App',
  components: {
    Header,
    LoginModal
  }
}
</script>

<style lang="scss">
#app {
  max-width: 100vw;
  position: relative;
  width: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #f6f6f6;
}
</style>
