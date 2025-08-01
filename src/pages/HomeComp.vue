<template>
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-6">
        <p>
          ❤️Welcome to my website❤️
          <br>
          This website is developed using the Vue.js framework.
          The project structure follows a component-based architecture, with logical separation of files into <strong>components</strong> and <strong>pages</strong>  directories.
          Routing is handled by Vue Router, with each route mapped to a specific view.
          The user interface is styled using Bootstrap classes to ensure responsiveness and consistency.
          The codebase is modular and maintainable, facilitating future development and scalability.
        </p>

        <router-link class="btn btn-dark" :to="{name:'users'}">Users</router-link>
        <router-link class="btn btn-light ms-3" :to="{name:'posts'}">Posts</router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>