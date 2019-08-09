<template>
<div class="top-nav bg-danger">
<div class="container">
<nav class="navbar navbar-inverse navbar-expand-md">
  <div class="container-fluid">
    <div class="navbar-header">
      <a class="navbar-brand text-light" href="#"><img src="@/assets/logo.png"/>AdoptMe.org</a>
    </div>
    <ul class="nav navbar-right text-light">
      <li><a href="#">WHO we are</a></li>
      <li><a href="#"> WHAT we do</a></li>
      <li><a href="#"> EVENTS Adoption</a></li>
    </ul>
  </div>
</nav>
</div> 
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import "@/assets/styles/_variables.scss";

.navbar {
    .navbar-header{
        a{
            font-size: 2em;
        }
    }
    li{
        padding: 10px;
        a{
            font-family: $font-family-primary;
            color: white;
        }
    }
}



</style>
