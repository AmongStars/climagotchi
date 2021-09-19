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
      <a href="map-start-instructions" target="_self">
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

@media only screen and (max-width: 1024px) {
  .text-box {
    margin-bottom: 5rem;
  }
}

@media only screen and (max-width: 420px) {
  .text-box {
    margin-top: 2rem;
    margin-bottom: 2rem;
    padding: 1rem;
    width: 15em;
  }

  .text-box-title {
    font-size: 1rem;
  }

  .text-box-info {
    font-size: 0.75rem;
    width: 10rem;
  }
}
</style>
