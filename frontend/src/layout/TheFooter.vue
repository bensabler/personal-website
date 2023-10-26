<template>
  <footer class="footer bg-dark py-3 mt-auto text-white">
    <div class="container d-flex justify-content-center">
      <span>Ben Sabler &copy;{{ new Date().getFullYear() }} </span>
    </div>
  </footer>
</template>

<script></script>

<style scoped>
* {
  border: 1px red solid;
}

footer {
  position: absolute;
  left: 0;
  bottom: 0;
  height: 15vh;
  width: 100%;
}

span {
  font-family: "Sofia-Pro", sans-serif;
  font-weight: 300;
  font-size: 0.9rem;
  letter-spacing: 0.1rem;
  color: #fff;
}
</style>
