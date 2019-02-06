<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div class="navbar-menu">
      <div class="navbar-start">
        <a class="navbar-item" href="/">Home</a>
        <a class="navbar-item" href="/about-us">About</a>
        <a class="navbar-item" href="/plants">Plants</a>
        <div class="navbar-item has-dropdown is-hoverable is-hidden">
          <a class="navbar-link">Plants</a>

          <div class="navbar-dropdown">
            <a class="navbar-item">Indoor</a>
            <a class="navbar-item">Outdoor</a>
            <a class="navbar-item">Pots</a>
            <hr class="navbar-divider">
            <a class="navbar-item">Report an issue</a>
          </div>
        </div>
      </div>

      <a class="navbar-item navbar-center logo" href="https://bulma.io">
          <h1><strong>PLANT</strong>VILLE PH</h1>
      </a>

      <div class="navbar-end">
          <div class="navbar-item">
          <div class="buttons">
              <a class="button is-primary">
              <strong>Sign up</strong>
              </a>
              <a class="button is-light">
              Log in
              </a>
          </div>
          </div>
      </div>
    </div>

  </nav>
</template>

<style scoped>
  .logo {
    font-size: 18px;
  }
  .navbar {
    min-height: 5.25em;
    background-color: #E1F3E2;
  }
</style>
