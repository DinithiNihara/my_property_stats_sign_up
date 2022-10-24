<template>
  <v-row class="app" justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <MainHeading>Register</MainHeading>
      <p class="paragraph">
        Let's get you started with the best property optimizing tool!
      </p>
      <v-row>
        <v-col cols="12" sm="6">
          <h4>First name</h4>
          <TextInput />
        </v-col>
        <v-col cols="12" sm="6">
          <h4>Last name</h4>
          <TextInput />
        </v-col>
      </v-row>

      <h4>Email address</h4>
      <TextInput />

      <h4>Date of birth</h4>
      <DateInput></DateInput>

      <h4>Password</h4>
      <PasswordInput />

      <h4>Confirm password</h4>
      <PasswordInput />

      <v-row align="center">
        <v-col cols="12" sm="1"><CheckboxInput /></v-col>
        <v-col cols="12" sm="11"
          ><span>
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
          </span></v-col
        >
      </v-row>

      <PrimaryButton>Register</PrimaryButton>
      <br /><br />
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
import PrimaryButton from "../components/buttons/PrimaryButton.vue";
import TextInput from "../components/inputs/TextInput.vue";
import PasswordInput from "../components/inputs/PasswordInput.vue";
import CheckboxInput from "../components/inputs/CheckboxInput.vue";
import MainHeading from "../components/headings/MainHeading.vue";
import DateInput from "../components/inputs/DateInput.vue";

export default {
  name: "IndexPage",
  components: {
    PrimaryButton,
    TextInput,
    PasswordInput,
    CheckboxInput,
    MainHeading,
    DateInput,
  },
};
</script>
