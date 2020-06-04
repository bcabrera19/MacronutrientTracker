<template>
  <div id="app">
    <b-container>
      <b-row align-h="center" class="mt-5">
        <b-col cols="5">
          <b-card class="p-3">
            <h3 class="mb-4 text-center">Fit Food Tracker</h3>
            <form>
              <div class="form-group">
                <input type="email" class="form-control" v-model="form.email" required placeholder="Phone number, username or email">
              </div>
              <div class="form-group">
                <input type="password" class="form-control" v-model="form.password" required placeholder="Password">
              </div>
              <button type="submit" class="btn btn-primary">Log In</button>
            </form>
          </b-card>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'App',

  data() {
    return {
      form: {
        email: '',
        password: '',

      }
    }
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css?family=Lato:400,700');

  body {
    background: #EEF1F4;
    font-family: 'Lato', sans-serif;
  }

</style>
