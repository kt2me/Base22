<template>
<div class="footer p-4 page-footer">
<div class="container">
    <div class="row">
    <div class="col-3 text-light address">
        <a class="navbar-brand text-light" href="#"><img src="@/assets/logo.png"/>AdoptMe.org</a>
        <p class="mt-2">Main Street #1345</p>
        <p> Amazing City 45678</p>
    </div>

    <div class="col-5 text-center text-light">
    <nav class="navbar navbar-inverse navbar-expand-md">
    <ul class="nav navbar navbar-right text-light">
      <li><a href="#">WHO we are</a></li>
      <li><a href="#"> WHAT we do</a></li>
      <li><a href="#"> EVENTS Adoption</a></li>
    </ul>
    </nav> 
    </div>
    </div> 
</div>
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import "@/assets/styles/_variables.scss";




.address{
    p{
        line-height: 0px;
    }
}
</style>
