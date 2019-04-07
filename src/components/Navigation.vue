<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="/">
        <img src="@/assets/logo.svg" width="140" height="140">
      </a>

      <a
        role="button"
        class="navbar-burger burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasicExample"
      >
        <span aria-hidden="false"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-end">
        <div class="navbar-item">
          <strong>
            <a href="mailto:info@ti-ce.de">info@ti-ce.de</a>
          </strong>
        </div>
        <div class="navbar-item">
          <strong>
            <a href="tel:01632865080">0163 2865080</a>
          </strong>
        </div>
      </div>
    </div>
  </nav>
</template>


<script>
export default {
  name: "Navigation",
  data() {
    return {};
  },
  methods: {}
};
</script>

<style scoped>
.navbar-item img {
  max-height: 5rem;
}
.navbar-item a {
  color: black;
}
</style>
