<template>
  <NavBar></NavBar>
  <div class="container">
    <div class="row">
      <div class="col-md-6 d-block d-md-flex myText">
        <div class="text">
          <h1 class="mytitle">Exquisite Watches</h1>
          <h2 class="mytitle">Choose Luxury, <span style="color: #947F6C;">Choose Us</span></h2>
          <p  class="myP">
            Discover the Perfect Watch for Every Occasion and Elevate Your Style
          With Timeless Elegance and Precision Craftsmanship</p>
          <h1 class="mytitle">$4300.00</h1>
        </div>     
    </div>
      <div class="col-md-6 d-block d-md-flex">
        <img alt="Vue logo" src="./images/watch.png" class="myimage"/>
      </div>
    </div>
  </div>
  <div class="container">
  <CustomFooter></CustomFooter>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap"
import CustomFooter from './components/CustomFooter.vue'
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    CustomFooter,
    NavBar,
  }
}
</script>

<style>
#app {
  text-align: center;
  color: #2c3e50;
  background-color: #F4D4B8;
  min-height: 100vh; /* 100vh = 100% dell'altezza della finestra */
  min-width: 100vw; 
}

  .myText{
    padding: 3rem; margin-top: 3rem;
  }
.myimage{
  width: 25vw;
  margin-left: 2vw;
  padding-top: 3rem;
}
.myP{
  font-weight: bold; letter-spacing: 0em; margin-top: 3rem; margin-bottom: 3rem; font-size: larger;
}

.text{
  text-align: left;
}
.mytitle {
  color: white;
  font-weight: 800;
} 

.container {
  max-width: 1060px;
  margin: 0 auto;
}


@media (max-width: 768px) {
  
.text{
  text-align: center;
}
.myimage{
  width: 60vw;  margin-left: 0vw; padding-top: 0rem;
}
.myP{
    margin-top: 0.5rem; margin-bottom: 0.5rem; font-size: larger;
}
.myText{
    padding: 1.5rem; margin-top: 1rem;
  }

}
/*--------*/

</style>
