<template>
    <nav class="navbar navbar-expand-lg bg-white border-bottom py-3">
      <div class="container">
        <a class="navbar-brand fw-bold text-dark" href="#">
          <i class="bi bi-caret-down-fill me-1"></i>FASHION
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
          <ul class="navbar-nav gap-4">
            <li class="nav-item"><a class="nav-link text-dark fw-semibold" href="#">CATALOGUE</a></li>
            <li class="nav-item"><a class="nav-link text-dark fw-semibold" href="#">FASHION</a></li>
            <li class="nav-item"><a class="nav-link text-dark fw-semibold" href="#">FAVOURITE</a></li>
            <li class="nav-item"><a class="nav-link text-dark fw-semibold" href="#">LIFESTYLE</a></li>
          </ul>
        </div>
        <div class="d-none d-lg-block">
          <button class="btn btn-dark rounded-pill px-4 fw-semibold">SIGN UP</button>
        </div>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Navbar'
  }
  </script>
  
  <style scoped>
  .navbar-nav .nav-link:hover {
    color: #f39c12;
  }
  </style>
  