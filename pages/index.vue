<template>
  <v-row class="app" justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <h1 class="title">Register</h1>
      <br />
      <p class="paragraph">
        Let's get you started with the best property optimizing tool!
      </p>
      <div class="itemsLeft">
        <h4>First name:</h4>
        <input type="text" class="inputStyles" />
      </div>
      <div class="itemsRight">
        <h4>Last name:</h4>
        <input type="text" class="inputStyles" />
      </div>
      <br /><br /><br />
      <h4>Email address:</h4>
      <input type="text" class="textInput inputStyles" />
      <br /><br />
      <h4>Date of birth:</h4>
      <input type="date" class="textInput inputStyles" />
      <br /><br />
      <h4>Password:</h4>
      <input type="password" class="textInput inputStyles" />
      <br /><br />
      <h4>Confirm password:</h4>
      <input type="password" class="textInput inputStyles" />
      <br /><br />
      <input type="checkbox" />
      <span>
        I agree with the
        <a
          href="#"
          target="_blank"
          rel="noopener noreferrer"
          title="terms"
          class="link"
        >
          terms and conditions
        </a>
      </span>
      <br /><br />
      <button class="registerBtn">Register</button>
      <br /><br /><br /><br />
      <p align="center">
        Already have an account?
        <a
          href="#"
          target="_blank"
          rel="noopener noreferrer"
          title="login"
          class="link"
        >
          Login
        </a>
      </p>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
