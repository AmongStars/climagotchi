<template>
  <div class="bg-game">
    <img src="~/assets/images/logo.svg" class="logo" />
    <div class="text-box">
      <img src="~/assets/images/bubble.png" />
      <div class="text-box-text">
        <h2 class="text-box-title">Water pollution</h2>
        <p class="text-box-info">
          Here is the short video about surprising facts around the water. Did
          you know about them?
        </p>
      </div>
      <img src="~/assets/images/bubble.png" class="bubbles" />
    </div>
    <div class="buttons">
      <a href="task-1-start" target="_self">
        <button type="button" class="btn btn-secondary">Ready for quiz!</button>
      </a>
    </div>
  </div>
</template>

<style scoped>
.bg-game {
  background-size: 180% 150%;
  background-position: bottom left;
}

.logo {
  margin-right: 0;
  width: 30%;
}

.buttons {
  align-items: center;
}

.btn {
  width: 20rem;
}

.text-box {
  display: flex;
  flex-direction: row;
  width: 60em;
  margin-top: 2rem;
  margin-bottom: 5rem;
}

.text-box-text {
  margin-right: auto;
  margin-left: auto;
  align-self: center;
}

.bubbles {
  transform: scaleX(-1);
}
</style>
