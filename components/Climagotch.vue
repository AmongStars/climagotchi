<template>
  <div class="avatar-carousel">
    <VueSlickCarousel :arrows="true" :dots="true">
      <div class="avatar-animal">
        <img src="~/assets/images/bee.png" class="bee" />
        <p class="avatar-name">BeeBee</p>
      </div>
      <div class="avatar-animal">
        <img src="~/assets/images/leo.png" class="leo" />
        <p class="avatar-name">Snowy Leo</p>
      </div>
      <div class="avatar-animal">
        <img src="~/assets/images/norp.png" class="norp" />
        <p class="avatar-name">Norppiana</p>
      </div>
      <div class="avatar-animal">
        <img src="~/assets/images/pingi.png" class="pingi" />
        <p class="avatar-name">PingiPingi</p>
      </div>
      <div class="avatar-animal">
        <img src="~/assets/images/turt.png" class="turt" />
        <p class="avatar-name">Turtelito</p>
      </div>
    </VueSlickCarousel>
  </div>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "Climagotch",
  components: { VueSlickCarousel }
};
</script>
<style scoped>
.avatar-animal .bee {
  width: 80%;
  margin-left: auto;
  margin-right: auto;
}

.avatar-animal .leo,
.avatar-animal .turt {
  width: 45%;
  margin-left: auto;
  margin-right: auto;
}

.avatar-animal .norp {
  width: 50%;
  margin-left: auto;
  margin-right: auto;
}

.avatar-animal .pingi {
  width: 75%;
  margin-left: auto;
  margin-right: auto;
}

.avatar-name {
  text-align: center;
  font-weight: bold;
  margin-top: 1em;
}
</style>
