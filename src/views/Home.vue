<template>
  <div class="home">
    <div class="container">
      <div class="columns">
        <div class="column auto">
          <div class="text">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
          <div class="">
            <button type="button" class="button is-primary" name="button"><router-link :to="{ name: 'About'}">Learn more</router-link></button>
          </div>
        </div>
        <div class="column is-three-fifths">
          <div class="">
            <img src="@/assets/image1.jpg" alt="image1">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style media="screen">
  .text {
    margin-top: 45%;
  }
  img {
    margin-left: 20%;
  }
  p {
    margin-bottom: 25px;
  }
  a {
    color: black;
  }
</style>
