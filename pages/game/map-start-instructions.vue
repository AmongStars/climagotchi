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
      <a href="map-start-levels" target="_self">
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
  margin-bottom: 15rem;
}

@media only screen and (max-width: 1024px) {
  .text-box {
    margin-bottom: 5rem;
  }
}
</style>
