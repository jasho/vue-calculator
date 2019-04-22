<template>
  <div class='calculator'>
    <div class='display'>0</div>
    <div class='button'>C</div>
    <div class='button'>+/-</div>
    <div class='button'>%</div>
    <div class='button operator'>÷</div>
    <div class='button'>7</div>
    <div class='button'>8</div>
    <div class='button'>9</div>
    <div class='button operator'>x</div>
    <div class='button'>4</div>
    <div class='button'>5</div>
    <div class='button'>6</div>
    <div class='button operator'>-</div>
    <div class='button'>1</div>
    <div class='button'>2</div>
    <div class='button'>3</div>
    <div class='button operator'>+</div>
    <div class='button zero'>0</div>
    <div class='button'>.</div>
    <div class='button operator'>=</div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>

.calculator {
  margin: auto;
  width: 60vw;
  height: 60vh;
  font-size: 2rem;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(10vh, auto);
  border: 1px solid #111;
  line-height: 10vh;
}

.display {
  grid-column: 1 / 5;
  background-color: #ececec;
  border: 1px solid #111;
  font-size: 2.5rem;
  cursor: default;
}

.zero {
  grid-column: 1 / 3;
}

.button {
  background-color: #bfbfbf;
  border: 1px solid #111;
  cursor: pointer;
}

.operator {
  background-color: #acce33;
}

</style>
