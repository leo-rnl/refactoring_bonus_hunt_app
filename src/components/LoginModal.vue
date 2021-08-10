<script>
export default {
  name: 'LoginModal',
}
</script>

<template>
  <div class="modal">
    <h2 class="modal__title">Connectez-vous !</h2>
    <p class="modal__content">L'application sauvegarde tous vos Bonus Hunt.<br> Vous connecter permet de les retrouver en toutes circonstances.</p>
    <button class="button">Se connecter avec Google</button>
  </div>
</template>

<style lang="scss" scoped>

  .modal{
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }

</style>