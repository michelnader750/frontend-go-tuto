<template>
  <nav class="navbar bg-body-tertiary fixed-top navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img src="@/assets/cat.jpeg" alt="Logo" width="30" height="24" class="d-inline-block align-text-top">
        Gopher E-commerce
      </a>
      <!-- Dropdown button (burger button) -->
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <!-- Links -->
      <div class="collapse navbar-collapse" id="navbarScroll">
        <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">Plushes</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Clothes</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Accessories</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><UserIcon></UserIcon></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><CartIcon></CartIcon> Cart 0</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
import CartIcon from './icons/CartIcon.vue'
import UserIcon from "./icons/UserIcon.vue"
export default {
  name: "NavBar",
  components: {UserIcon, CartIcon}
}
</script>

<style>

</style>