<!-- <script setup>
import countryName from './data/data';

function colorpik(){
  const fastInp = document.querySelector('.fast').value
  const fastCreat = document.querySelector('.fastCreat')
  fastCreat.style.background = fastInp
  document.querySelector('.colo').innerHTML = fastInp
}
</script>

<template>
 <h1>Checking The Color</h1>
  <div class="fastCreat " v-for="(allcountry, index) in countryName" :key="index">
    <h4>{{ allcountry.country }}</h4>
    <code>{{ allcountry.city }}</code><br>
    <input type="color" name="" class="fast"  @input="colorpik">
    <p class="colo"> </p>
  </div>
</template>

<style scoped>
 .fastCreat{
  color: rgb(255, 255, 255);
  box-shadow: 0 0 4px 0 gray;
  border-radius: 6px;
  margin: 16px;
  padding: 10px;
 }
</style>
  -->



  <script setup>
import countryName from './data/data';

function colorpik(index){
  const fastInp = document.querySelector(`.fast[name='fast-${index}']`).value;
  const fastCreate = document.querySelectorAll('.fastCreate')[index];
  const colo = fastCreate.querySelector('.colo');

  fastCreate.style.background = fastInp;
  colo.innerHTML = fastInp;
}
</script>

  <template>
    <h1>Checking The Color</h1>
    <div class="fastCreate" v-for="(allcountry, index) in countryName" :key="index">
      <h4>{{ allcountry.country }}</h4>
      <code>{{ allcountry.city }}</code><br>
      <input type="color" :name="'fast-' + index" class="fast" @input="colorpik(index)">
      <p class="colo"></p>
    </div>
  </template>
  