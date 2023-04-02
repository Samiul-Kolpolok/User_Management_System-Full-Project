<script setup>
</script>
<template>
<nav class="navbar navbar-expand-lg bg-info bg-body-tertiary">
  <div class="container-fluid">
    <img src="../assets/kolpolok_limited_logo.png" alt="kolpolok_limited_logo" width="50 px" height="50 px" class="img-style" />
    <a class="navbar-brand" href="#">Kolpolok Limited</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto my-2 my-lg-0">
          <li class="nav-item dropdown">
             <a class="nav-link dropdown-toggle" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              <i class="bi bi-person-circle"></i>Admin
              </a>
         <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
           <li><h6 class="mx-3" @click="$router.push('/profile')">Profile</h6></li>
           <li><h6 class="mx-3" @click="$router.push('/settings')">Settings</h6></li>
        </ul>
          </li>
        </ul>
      </div>
  </div>
</nav>
</template>

<style>
.img-style {
  width: 50px;
  height: 50px;
}
</style>
