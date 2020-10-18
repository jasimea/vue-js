<template>
  <form class="form">
    <div class="form-group">
    <label for="exampleInputEmail1">First Name</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
  </div>
  <div class="form-group">
    <label for="exampleInputEmail1">Last Name</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
  </div>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>

</template>
<script>
export default {
  name:'Input'
}
</script>
<style scoped>
.form{
  position: relative;
    left: 13%;
    width: 30%;
    background: white;
}

.form-group {
    width: 40%;
    margin-top: 40px;
    margin-left: 30%;
}
.btn{
  margin-left: 30%;
  
}
.check-box{
  display: flex;
}
</style>