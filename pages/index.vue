<template>
  <div class="container">
    <div>
      <TicTacToe />
    </div>
  </div>
</template>

<script>
import TicTacToe from "~/components/TicTacToe"

export default {
  components: {
    TicTacToe
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
