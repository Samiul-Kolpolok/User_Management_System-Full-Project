<script>
import axios from 'axios';
export default {
  props: {
    msg: String, 
  },
  data(){
    return {
        user:{
            name:"",
            email:"",
            phonenumber:"",
            address:"",
            designation:"",
            department:""
        },
    }
  },
    created() {
    },
  methods:{
    onSubmit() {
      console.log(this.user);
      axios.post('http://127.0.0.1/api/create_user.php', this.user)
        .then(response => {
            console.log(response);
        })
        .catch(error => {
            console.log(error);
        });
  }
}}
</script>

<template>
    <form>
   <div class="mb-3">
    <label for="name" class="form-label">Name</label>
    <input type="text" class="form-control" id="name" v-model="user.name">
  </div>     
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" v-model="user.email">
  </div>
  <div class="mb-3"> 
    <label for="phone" class="form-label">Phone Number</label>
    <input type="text" class="form-control" id="phone" v-model="user.phonenumber">
  </div>  
  <div class="mb-3">
    <label for="address" class="form-label">Address</label>
    <input type="text" class="form-control" id="address" v-model="user.address">
  </div>
  <div class="mb-3">
    <label for="designation" class="form-label">Designation</label>
    <input type="text" class="form-control" id="designation" v-model="user.designation">
  </div>
  <div class="mb-3">
    <label for="designation" class="form-label">Department</label>
    <input type="text" class="form-control" id="designation" v-model="user.department">
  </div>
  
  <button type="submit" class="btn btn-primary" v-on:click.prevent = "onSubmit()">Submit</button>
</form>
</template>