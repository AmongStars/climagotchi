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
      <a href="water/start-quiz" target="_self">
        <button type="button" class="btn btn-secondary">Start journey!</button>
      </a>
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
  padding: 3rem 0;
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
