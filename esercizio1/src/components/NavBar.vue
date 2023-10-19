<template>
    <nav class="navbar navbar-expand-lg static-top custom-navbar" >
  <div class="container" >
    <a class="navbar-brand" href="#">
      <img src="../images/Logo.png" width="90">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item" >
          <a class="nav-link" href="#" style=" font-size: large; font-weight: bold;">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" style=" font-size: large; font-weight: bold;">Shop</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" style=" font-size: large; font-weight: bold;">Contact us</a>
        </li>
        <li class="nav-item">
          <button class="btn btn-dark" style=" font-size: large; font-weight: bold; border-radius: 20px;"><a>Sign up</a></button>
        </li>
      </ul>
    </div>
  </div>
</nav>  
</template>


<script>
export default {
  name: 'NavBar',
}
</script>

<style scoped>
header {
  width: 100%;
}

.nav-item{
  font-weight: 600;
  margin-left: 3rem;
  
}

.custom-navbar {
        background-color: rgba(73, 56, 46, 0.65); /* Colore di sfondo con opacità */
    }

.container{
    height: 90px;
}

@media (max-width: 768px) {
    .navbar-collapse {
        height: 100vh;
        font-size: large;
        align-items: center;
    }
    .navbar-brand {
        margin-left: 8vw;
    }
    .container{
        height: 100;
    }
}

</style>