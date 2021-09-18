<template>
  <div class="bg-game">
    <img src="~/assets/images/logo.svg" class="logo" />
    <div class="text-box">
      <p class="text-box-info">
        Learn with her how small actions can have big difference!
      </p>
      <img src="~/assets/images/bee-sad.png" class="avatar-sad" />
    </div>
    <div class="buttons">
      <b-link to="map-start-journey"
        ><b-button>Start journey!</b-button></b-link
      >
    </div>
  </div>
</template>

<style scoped>
.logo {
  margin-right: 0;
  width: 30%;
}

.buttons {
  align-items: center;
}

.text-box {
  display: flex;
  flex-direction: row;
  margin-bottom: 2rem;
}

.text-box-info {
  align-self: center;
}

.avatar-sad {
  width: 40%;
  margin: 0 2rem;
}

.btn {
  width: 20rem;
}
</style>
