<template>
  <div class="container">
    <div class="tile is-ancestor">
      <div class="tile is-parent">
        <article class="tile is-child box">
          <p class="title">12345678</p>
          <p class="subtitle">Lobby code</p>
        </article>
      </div>
      <div class="tile is-parent">
        <article class="tile is-child box">
          <p class="title"> xXx_qUiZlOrd3_xXx </p>
          <p class="subtitle">Nickname</p>
        </article>
      </div>
      <div class="tile is-parent">
        <article class="tile is-centered is-child box" >
          <b-button class="is-danger is-large">Leave Game</b-button>
        </article>
      </div>
    </div>
    <nuxt />
  </div>

</template>

<script>
export default {
  data () {
    return {
      items: [
        {
          title: 'Home',
          icon: 'home',
          to: { name: 'index' }
        },
        {
          title: 'Inspire',
          icon: 'lightbulb',
          to: { name: 'inspire' }
        },
        {
          title: 'Game',
          icon: 'gamepad',
          to: { name: 'game' }
        }
      ]
    }
  }
}
</script>
