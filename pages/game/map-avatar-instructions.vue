<template>
  <div class="bg-game">
    <img src="~/assets/images/logo.svg" class="logo" />
    <div class="text-box">
      <p class="text-box-info">
        The Beebee is very sad. She thinks that she can do nothing about the
        world around her.
      </p>
      <img src="~/assets/images/bee-sad.png" class="avatar-sad" />
    </div>
    <div class="buttons">
      <a href="map-start-journey" target="_self">
        <button type="button" class="btn btn-secondary">Next</button>
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
  align-items: end;
}

.text-box {
  display: flex;
  flex-direction: row;
  padding: 3rem 0;
  margin-bottom: 14rem;
}

.text-box-info {
  align-self: center;
}

.avatar-sad {
  width: 40%;
  margin: 0 2rem;
}
</style>
