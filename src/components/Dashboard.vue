<script setup>

</script>

<template>
<h1>Dashboard</h1>
<nav class="navbar navbar-expand-lg bg-light bg-body-tertiary">
  <div class="container-fluid p-1 flex-grow-1">
    <a class="navbar-brand" href="#">Dashboard</a>
  </div>
</nav>
<div class="d-sm-flex">
<div class="card bg-primary my-2 mx-1" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title">User</h5>
    <i class="bi bi-person bi-lg custom-size"></i> <br>
    <span>1</span>
  </div>
</div>
<div class="card bg-success my-2 mx-1" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title">Department</h5>
    <i class="bi bi-house-door-fill bi-lg custom-size"></i> <br>
    <span>2</span>
  </div>
</div>
<div class="card bg-warning my-2 mx-1" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title">Notice</h5>
    <i class="bi bi-envelope-fill bi-lg custom-size"></i> <br>
    <span>3</span>
  </div>
</div>
<div class="card bg-danger my-2 mx-1" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title">Archive</h5>
    <i class="bi bi-archive bi-lg custom-size"></i> <br>
    <span>4</span>
  </div>
</div>
</div>
<nav class="navbar navbar-expand-lg bg-light bg-body-tertiary">
  <div class="container-fluid flex-grow-1">
    <a class="navbar-brand" href="#">Your Details</a>
  </div>
</nav>
<nav class="navbar navbar-expand-lg bg-warning bg-body-tertiary">
  <div class="container-fluid flex-grow-1">
    <a class="navbar-brand" href="#">Name</a>
  </div>
</nav>
<nav class="navbar navbar-expand-lg bg-success bg-body-tertiary">
  <div class="container-fluid flex-grow-1">
    <a class="navbar-brand" href="#">Email</a>
  </div>
</nav>
<nav class="navbar navbar-expand-lg bg-primary bg-body-tertiary">
  <div class="container-fluid flex-grow-1">
    <a class="navbar-brand" href="#">Phone Number</a>
  </div>
</nav>
<nav class="navbar navbar-expand-lg bg-danger bg-body-tertiary">
  <div class="container-fluid flex-grow-1">
    <a class="navbar-brand" href="#">Address</a>
  </div>
</nav>
<nav class="navbar navbar-expand-lg bg-secondary bg-body-tertiary">
  <div class="container-fluid flex-grow-1">
    <a class="navbar-brand" href="#">Designation</a>
  </div>
</nav>
</template>

<style>
.bi.custom-size {
  font-size: 3.5rem;
}

.custom-green {
    color: #ffffff; /* text color */
    background-color: #28a745; /* background color */
    border-color: #28a745; /* border color */
}

.custom-red {
    color: #ffffff; /* text color */
    background-color: #DC1625  ; /* background color */
}
</style>