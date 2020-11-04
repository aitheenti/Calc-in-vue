<template>
  <div class="calculator">
    <div class="display"> {{Math.random()}}</div>
    <div>A/C</div>
    <div>+/-</div>
    <div>%</div>
    <div>/</div>

    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>*</div>

    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>-</div>
    
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>+</div>

    <div class="zero">0</div>
    <div>.</div>
    <div>=</div>
  </div>
</template>
  
<script>


</script>

<style>
.calculator {
  display: grid;
  max-width: 50%;
  margin: auto;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
  }
.display {
  grid-column: 1/5;
  background-color: aqua;
}
.zero {
  grid-column: 1/3;

  }
</style>