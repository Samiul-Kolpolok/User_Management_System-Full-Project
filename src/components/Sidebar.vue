<script setup>
</script>
<template>
  <nav class="navbar navsidebar navbar-expand-lg bg-warning bg-body-tertiary">
    <div class="d-sm-flex-column mx-5 ">
      <div class="d-flex">
        <i class="bi bi-speedometer2 me-2"></i> 
        <h5 class="mx-1" @click="$router.push('/dashboard')">Dashboard</h5>
      </div> 
      <hr>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto my-2 my-lg-0">
          <li class="nav-item">
            <button class="btn btn-outline-primary my-3" @click="$router.push('/userlists')">UserLists</button> <br>
            <button class="btn btn-outline-primary my-3" @click="$router.push('/addnewuser')">Add New User</button> <br>
            <button class="btn btn-outline-primary my-3" @click="$router.push('/about')">About</button> <br>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style>
.navsidebar{
  height:100%
}
</style>