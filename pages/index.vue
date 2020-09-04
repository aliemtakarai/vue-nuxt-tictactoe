<template>
  <div>
    <div class="container">
      <div>
        <TicTacToe />
      </div>
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
  min-height: 75vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
