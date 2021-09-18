<template>
  <div>
    <img src="~/assets/images/logo.svg" class="logo" />
    <div class="login-form">
      <b-form-input
        v-model="teamName"
        placeholder="Your team's name here"
      ></b-form-input>
      <b-form-input
        v-model="userName"
        placeholder="Please enter your name"
      ></b-form-input>
      <b-form-input placeholder="Please enter password here"></b-form-input>
    </div>
    <div class="buttons">
      <b-link to="avatar/choose-avatar"><b-button>Submit</b-button></b-link>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      teamName: "",
      userName: ""
    };
  }
};
</script>
