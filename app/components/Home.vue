<template>
  <Page>
    <StackLayout class="form">
      <StackLayout class="input-field">
        <TextField class="input"></TextField>
      </StackLayout>

      <StackLayout class="input-field">
        <TextField class="input"></TextField>
      </StackLayout>

      <Button text="Log In" class="btn btn-primary"></Button>
    </StackLayout>
  </Page>
</template>

<script lang="ts">
import Vue from 'nativescript-vue';

export default Vue.extend({
  computed: {
    message() {
      return 'Blank {N}-Vue app';
    },
  },

  methods: {
    logMessage() {
      console.log('You have tapped the message!');
    },
  },
});
</script>

<style>
.page {
  align-items: center;
  flex-direction: column;
}
.form {
  margin-left: 30;
  margin-right: 30;
  flex-grow: 2;
  vertical-align: middle;
}
</style>
