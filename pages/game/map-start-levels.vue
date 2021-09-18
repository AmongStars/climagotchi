<template>
  <div class="bg-game">
    <img src="~/assets/images/logo.svg" class="logo" />
    <div class="levels">
      <div class="levels-1-col">
        <div class="text-box">
          <p class="text-box-info">
            Waste management
          </p>
        </div>
        <div class="text-box">
          <p class="text-box-info">
            Overconsumption
          </p>
        </div>
        <div class="text-box">
          <p class="text-box-info">
            Water pollution
          </p>
        </div>
      </div>
      <div class="levels-2-col">
        <div class="text-box">
          <p class="text-box-info">
            Transportation
          </p>
        </div>
        <div class="text-box">
          <p class="text-box-info">
            Finish
          </p>
        </div>
        <div class="text-box">
          <p class="text-box-info">
            Electricity &amp; energy
          </p>
        </div>
        <div class="text-box">
          <p class="text-box-info">
            Air pollution
          </p>
        </div>
      </div>
      <div class="levels-3-col">
        <div class="text-box">
          <p class="text-box-info">
            Natural disasters
          </p>
        </div>
        <div class="text-box">
          <p class="text-box-info">
            Diet &amp; agriculture
          </p>
        </div>
        <div class="text-box">
          <p class="text-box-info">
            Environmental health
          </p>
        </div>
      </div>
      <div class="levels-4-col">
        <div class="text-box">
          <p class="text-box-info">
            Global warming
          </p>
        </div>
        <div class="text-box">
          <p class="text-box-info">
            Deforestation
          </p>
        </div>
        <div class="text-box">
          <p class="text-box-info">
            Animal extinction
          </p>
        </div>
      </div>
    </div>
    <div class="buttons">
      <b-link to=""><b-button>Next</b-button></b-link>
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
  padding: 0.5rem;
  margin-top: 0;
  margin-bottom: 0;
  margin-right: 0;
  margin-left: 0;
  width: 15em;
}

.text-box-info {
  margin-bottom: 0;
}

.levels {
  display: flex;
  flex-direction: row;
}

.levels-1-col,
.levels-2-col,
.levels-3-col,
.levels-4-col {
  flex-direction: column;
}

.levels-1-col .text-box {
  margin-top: 13rem;
  margin-left: 0.5rem;
}

.levels-2-col .text-box {
  margin-top: 7rem;
  margin-left: 5rem;
}

.levels-2-col .text-box:nth-child(2) {
  margin-top: 4rem;
  margin-left: 15rem;
}

.levels-2-col .text-box:nth-child(3) {
  margin-top: 9rem;
  margin-left: 2rem;
}

.levels-2-col .text-box:nth-child(4) {
  margin-top: 3rem;
  margin-left: 10rem;
}

.levels-3-col .text-box {
  margin-top: 10rem;
  margin-left: 5rem;
}

.levels-3-col .text-box:nth-child(2) {
  margin-top: 14rem;
  margin-left: 5rem;
}

.levels-3-col .text-box:nth-child(3) {
  margin-top: 4rem;
  margin-left: 0rem;
}

.levels-4-col .text-box {
  margin-top: 6rem;
  margin-left: 2rem;
}

.levels-4-col .text-box:nth-child(2) {
  margin-top: 13rem;
  margin-left: 1rem;
}

.levels-4-col .text-box:nth-child(3) {
  margin-top: 6rem;
  margin-left: 3rem;
}
</style>
