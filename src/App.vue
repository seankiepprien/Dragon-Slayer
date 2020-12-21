<template>
  <div id="app">
    <div id="title" class="container">
      <h1>Dragon Slayer</h1>
    </div>
    <div id="player" class="container">
      <h2>Player's health</h2>
      <div class="healthbar">
        <div class="healthbar_value player"></div>
      </div>
    </div>
    <div id="monster" class="container">
      <h2>Monster's health</h2>
      <div class="healthbar">
        <div class="healthbar_value monster"></div>
      </div>
    </div>
    <div id="playerActions" class="container">
    <button id="attack">Attack</button>
    <button id="specialAttack">Special Attack</button>
    <button id="heal">Heal</button>
    <button id="surrender">Surrender</button>
    </div>
  </div>
</template>

<script>

export default {
  //TODO: 
}
</script>

<style>
@import "css/style.css";
</style>
