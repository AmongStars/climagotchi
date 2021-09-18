<template>
  <div class="bg-game">
    <img src="~/assets/images/logo.svg" class="logo" />
    <div class="text-box">
      <h2 class="text-box-title">Welcome!</h2>
      <p class="text-box-info">
        Let’s start your journey towards sustainable life
      </p>
    </div>
    <div class="buttons">
      <b-link to="map-start-instructions"><b-button>Next</b-button></b-link>
    </div>
  </div>
</template>

<style scoped>
.logo {
  margin-right: 0;
  width: 30%;
}

.buttons {
  align-items: end;
}
</style>
