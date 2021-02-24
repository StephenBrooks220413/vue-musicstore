<template>
  <div id="nav">
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg fixed-top navbar-light bg-light">
      <!-- Container wrapper -->
      <div class="container-fluid">
        <!-- Navbar brand -->
        <router-link class="navbar-brand" to="/">
          <i class="fab icon fa-servicestack"></i>
        </router-link>

        <!-- Toggle button -->
        <button
          class="navbar-toggler"
          type="button"
          data-mdb-toggle="collapse"
          data-mdb-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>

        <!-- Collapsible wrapper -->
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <!-- Left links -->
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="nav-link active" to="/">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/about"
                >About</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/contact"
                >Contact</router-link
              >
            </li>
            <!-- Navbar dropdown -->
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-mdb-toggle="dropdown"
                aria-expanded="false"
              >
                Dropdown
              </a>
              <!-- Dropdown menu -->
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li>
                  <router-link lass="dropdown-item" to="/">Action</router-link>
                </li>
                <li>
                  <router-link lass="dropdown-item" to="/">Action</router-link>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <router-link lass="dropdown-item" to="/">Action</router-link>
                </li>
              </ul>
            </li>
          </ul>
          <!-- Left links -->

          <!-- Search form -->
          <form class="d-flex input-group w-auto">
            <a href="">
              <i class="fas icon fa-envelope fa-lg"></i>
              <span class="badge rounded-pill badge-notification bg-danger"
                >1</span
              >
            </a>
            <a href="">
              <i class="far icon fa-user fa-lg"></i>
              <span
                class="badge rounded-pill badge-notification bg-danger"
              ></span>
            </a>
          </form>
        </div>
        <!-- Collapsible wrapper -->
      </div>
      <!-- Container wrapper -->
    </nav>
  </div>
  <router-view />
</template>

<style lang="scss">
@import "~mdb-ui-kit/css/mdb.min.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding-bottom: 5px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.icon {
  padding: 9px;
}
</style>
