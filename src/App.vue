<template>
  <div id="page-container">
    <nav-bar />
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-12 jumbotron d-flex justify-content-start align-items-end">
          <div class="m-5 jumbotron-header">
            <h1 class="text-danger">This is your new family</h1>
            <button type="button" class="btn btn-danger">Adopt Now</button>

          </div>
        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <div class="card purple-card pt-2">
              <p class="ml-4">AMAZING PEOPLE</p>
              <img src="@/assets/girl.png"/>
              <div class="card-bottom-text p-4">
              <h6 class="amazing-people-text"> Amazing people making a difference every single day. Join us now and be a part of a community that is changing the world.</h6>
              <button type="button" class="btn btn-light join-btn">Join Us</button>

              </div>
            </div>
          </div>
          <div class="col-md-8">
            <div class="card bg-danger testimonial pt-2">
              <p class="ml-4">TESTIMONAL OF THE MONTH</p>
              <img src="@/assets/testimonial.jpg" />
              
            </div>
          </div>
        </div>
      </div>


      <div class="container">
      <div class="row">
      <div class="col-5">
      <ul class="nav navbar navbar-right bottom-links p-3">
      <li><a href="#"><h4>Programs</h4></a></li>
      <li><a href="#"> <h4>Associated Companies</h4></a></li>
      </ul>
      </div>
    </div>
      </div>

      <div class="container">
        <div class="row d-flex align-items-center"> 
          <div class="col-4 friend-in-trouble">
            <img src="@/assets/friend-in-trouble.png" class="about-img"/>
          </div>
          <div class="col-5">
          <h6 class="text-gray"> Evaluate of each dog by a specialist who determines what training is needed to make your friend a better family member.</h6>
          <button type="button" class="btn btn-outline-danger">Leer Mas</button>

          </div>
      </div>
      <div class="row mb-4 d-flex align-items-center"> 
          <div class="col-4 franklin mt-4">
            <img src="https://images.unsplash.com/photo-1503256207526-0d5d80fa2f47?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=633&q=80" class="about-img"/>
          </div>
          <div class="col-5">
              <h6 class="text-gray">Evaluate of each dog by a specialist who determines what training is needed to make your friend a better family member.</h6>
              <button type="button" class="btn btn-outline-danger">Leer Mas</button>
          </div>
       </div> 
</div>
</div>

  <bottom-footer class="footer"/>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
import BottomFooter from "@/components/BottomFooter.vue";


import "bootstrap";
import "bootstrap/dist/css/bootstrap.min.css";

export default {
  name: "app",
  components: {
    NavBar,
    BottomFooter,
  }
};
</script>

<style lang="scss">
@import "@/assets/styles/_variables.scss";

#page-container{
  margin: 0;
  height: 100%;
  width: 100%;
  font-family: $font-family-primary;

}

#content-container {
  position: relative;
  min-height: 100%;
  padding-bottom: 20vh;
}
.jumbotron {
  padding: 0;
  background-image: url("assets/dogs.jpg");
  width: 100%;
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 50vh;
  font-family: $font-family-secondary;
  border-radius: 0;
}
  .purple-card{
  background-color: $color-blue;
  color: white;

  .join-btn{
    color: $color-blue;
    outline-color: $color-blue;
  }
}

.gray-text{
  color: $color-gray;
}
.testimonial{
  color:white;
}

  .bottom-links li a{
    color: $color-blue;
    font: $font-family-secondary;
  }


  .about-img{ 
    width: 30vh;
    height: 30vh;
    margin: auto;
  }
  .card-bottom-text{
    background-color: white;
    color: black;
  }

  .footer{
    background-color: $color-blue;
    border: 2rem red;
    height: 20vh;
    width: 100%;
    padding: 3rem;
}
</style>
