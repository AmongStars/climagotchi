<template>
  <div>
    <img src="~/assets/images/logo.svg" class="logo" />
    <h3 class="avatar-title">Choose your ClimaGotch</h3>
    <div class="avatar-options">
      <Climagotch />
    </div>
    <div class="buttons">
      <a href="../game/map-start" target="_self">
        <button type="button" class="btn btn-secondary">Next</button>
      </a>
    </div>
  </div>
</template>

<script>
import Climagotch from "../../components/Climagotch";

export default {
  data() {
    return {
      teamName: ""
    };
  },
  components: {
    Climagotch
  }
};
</script>

<style scoped>
.logo {
  margin-right: 0;
  width: 30%;
}

.avatar-title {
  text-align: center;
  font-weight: bold;
  margin-bottom: 2rem;
}

.buttons {
  align-items: end;
}

.avatar-options {
  width: 50%;
  margin-right: auto;
  margin-left: auto;
}

@media only screen and (max-width: 768px) {
  .buttons {
    align-items: center;
  }

  .avatar-title {
    font-size: 1.5rem;
  }
}
</style>
