<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid container">
      <a class="logo-text navbar-brand" href="#">Logo</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="flex gap-3 navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link Home_link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About us</a>
          </li>
          <li class="nav-item">
            <a class="navbar-btn sign_up btn" href="#">Sign Up</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script lang="ts" setup>
import { ref } from "vue";
const test = ref(0);
</script>

<style>
.navbar {
  background-color: #ECF6FF !important;
}

.navbar a {
  color: black;
  font-size: 16px;
  font-weight: 600;
}

.navbar .logo-text {
  color: #0086FF;
  font-size: 40px;
  font-weight: 700;
}

.navbar a:hover {
  color: #395B64;
}

.navbar-btn {
  border: none;
  background: rgba(255, 255, 255, 0.1)
}

.sign_up {
  background-color: #0086FF;
  color: white !important;
}

.Home_link {
  color: #0086FF !important;
}
</style>
