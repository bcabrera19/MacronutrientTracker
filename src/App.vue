<template>
  <div id="app">
    <nav class="navbar nav-background">
      <a class="navbar-brand" href="#">
        <img src="assets/logo.png" width="30" height="30" class="d-inline-block align-top" alt="">
        Fit Food Tracker
      </a>

    <button class="btn btn-primary" type="submit">+</button>
    </nav>

    <div class="container list">
      <div class="row align-items-start text-center">
        <div class="col-5">
          <h5>Description</h5>
        </div>
        <div class="col-sm">
          <h5>Calories</h5>
        </div>
        <div class="col-sm">
          <h5>Carbs</h5>
        </div>
        <div class="col-sm">
          <h5>Protein</h5>
        </div>
        <div class="col-sm">
          <h5>Fat</h5>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style>
  @import url('https://fonts.googleapis.com/css?family=Lato:400,700');

  body {
    background-image: #EEF1F4;
  }

  .nav-background {
    background: rgb(13, 82, 17);
  }

  .navbar-brand {
    color: #EEF1F4;
  }

  .navbar-brand:hover {
    color: #EEF1F4;
  }

  .list {
    background: #EEF1F4;
  }


</style>
