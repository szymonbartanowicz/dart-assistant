<template>
  <v-app>
    <v-main>
      <Board/>
    </v-main>
  </v-app>
</template>

<script>
import Board from './components/Board.vue'

export default {
  name: 'App',

  components: {
    Board,
  },

  data: () => ({
    //
  }),
}
</script>
