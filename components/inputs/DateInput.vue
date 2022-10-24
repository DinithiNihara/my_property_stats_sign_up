<template>
  <div>
    <v-menu
      ref="menu"
      :close-on-content-click="false"
      transition="scale-transition"
      offset-y
      min-width="auto"
    >
      <template v-slot:activator="{ on, attrs }">
        <v-text-field
          flat
          solo
          height="44px"
          label="Select"
          background-color="rgb(170, 165, 255, 0.2);"
          readonly
          v-bind="attrs"
          v-on="on"
        ></v-text-field>
      </template>
      <v-date-picker
        :max="
          new Date(Date.now() - new Date().getTimezoneOffset() * 60000)
            .toISOString()
            .substr(0, 10)
        "
        min="1950-01-01"
        color="#645CFC"
      ></v-date-picker>
    </v-menu>
  </div>
</template>
<script>
export default {};
</script>
