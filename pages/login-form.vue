<template>
  <div>
    <img src="~/assets/images/logo.svg" class="logo" />
    <div class="login-form">
      <input
        type="text"
        placeholder="Your team's name here"
        v-model="teamName"
        class="form-control"
      />
      <input
        type="text"
        placeholder="Please enter password here"
        class="form-control"
      />
    </div>
    <div class="buttons">
      <a href="/game/map-start" target="_self">
        <button type="button" class="btn btn-secondary">Next</button>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      teamName: ""
    };
  }
};
</script>

<style scoped>
.login-form input {
  margin-bottom: 2em;
  background-color: #ede682;
  box-shadow: 4px 6px #a2a0a0;
}

.form-control {
  display: block;
  width: 100%;
  height: calc(1.5em + 0.75rem + 2px);
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #495057;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ced4da;
  border-radius: 0.25rem;
  transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

@media only screen and (max-width: 600px) {
  .login-form {
    width: 250px;
    max-width: 250px;
    margin-top: 3rem;
  }
}
</style>
