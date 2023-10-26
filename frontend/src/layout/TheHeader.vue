<template>
  <nav class="navbar navbar-expand-lg">
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
        <ul class="navbar-nav pe-2 pt-4">
          <li class="nav-item">
            <a class="nav-link ms-auto text-lg-center" href="#">PROJECTS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link ms-auto text-lg-center" href="#">PHOTOGRAPHY</a>
          </li>
          <li class="nav-item">
            <a class="nav-link ms-auto text-lg-center" href="#">BLOG</a>
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

ul li a {
  width: 165px;
  padding: 8px 15px;
  margin: 0;
  transition: all 0.5s ease;
}

.brand-one {
  font-weight: 200;
}
.brand-two {
  font-weight: 500;
}
</style>
