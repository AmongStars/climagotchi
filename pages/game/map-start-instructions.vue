<template>
  <div class="bg-game">
    <img src="~/assets/images/logo.svg" class="logo" />
    <div class="text-box">
      <p class="text-box-info">
        Here you can see twelve levels - each representing different climate
        issue
      </p>
    </div>
    <div class="buttons">
      <b-link to="map-start-levels"><b-button>Next</b-button></b-link>
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
