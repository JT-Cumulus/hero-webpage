<template>
  <div class="about">
    <h1>This is an about page</h1>

    <img
      :src="https://static.wikia.nocookie.net/dota2_gamepedia/images/e/ed/Centaur_Warrunner_icon.png/revision/latest"
    />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
