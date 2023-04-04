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
<br>
<nav class="navbar navbar-expand-lg bg-light bg-body-tertiary">
  <div class="container-fluid flex-grow-1">
    <a class="navbar-brand" href="#">Your Details</a>
  </div>
</nav> 
<br>
<table class="table table-success">
  <tbody>
    <tr>
      <td>Name</td>
      <td>S. M. Samiul Alam</td>
    </tr>
    <tr>
      <td>Email</td>
      <td>samiul.kolpolok@gmail.com</td>
    </tr>
    <tr>
      <td>Phone number</td>
      <td>01580611615</td>
    </tr>
    <tr>
      <td>Designation</td>
      <td>Web Developer</td>
    </tr>
    <tr>
      <td>Department</td>
      <td>Web Technology</td>
    </tr>
  </tbody>
</table>
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