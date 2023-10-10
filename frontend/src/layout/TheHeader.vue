<template>
  <nav class="navbar p-3 navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <span class="brand-one">BEN </span>
        <span class="brand-two">SABLER</span>
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav folio-link">
          <li class="nav-item">
            <a class="nav-link" href="#">ABOUT</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">RESUME</a>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              PROJECTS
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Project 1</a></li>
              <li><a class="dropdown-item" href="#">Project 2</a></li>
              <li><a class="dropdown-item" href="#">Project 3</a></li>
            </ul>
          </li>
        </ul>
        <ul class="navbar-nav ms-auto user-link">
          <li class="nav-item">
            <a class="nav-link" href="#">LOGIN</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">SIGN UP</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">LOGOUT</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script></script>

<style scoped>
.navbar-brand {
  font-family: "Sofia-Pro", sans-serif;
  font-size: 1.4rem;
  letter-spacing: 0.1rem;

  color: #000;
}

.nav-link {
  font-family: "Sofia-Pro", sans-serif;
  font-weight: 300;
  font-size: 1.2rem;
  letter-spacing: 0.1rem;
  color: #000;
}

.nav-link:hover,
.nav-link:focus {
  font-weight: 500;
}

.brand-one {
  font-weight: 200;
}
.brand-two {
  font-weight: 500;
}
</style>
