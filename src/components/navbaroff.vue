<template>
  <nav class="navbar bg-dark fixed-top">
    <div class="container-fluid">
      <a class="navbar-brand text-white" href="#"
        ><i class="fa-brands fa-cloudflare"></i
      ></a>
      <button
        class="navbar-toggler bg-white"
        type="button"
        data-bs-toggle="offcanvas"
        data-bs-target="#offcanvasNavbar"
        aria-controls="offcanvasNavbar"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="offcanvas offcanvas-end"
        tabindex="-1"
        id="offcanvasNavbar"
        aria-labelledby="offcanvasNavbarLabel"
      >
        <div class="offcanvas-header">
          <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Navigate <i class="bi bi-compass"></i></h5>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="offcanvas"
            aria-label="Close"
          ></button>
        </div>
        <div class="offcanvas-body">
          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>

            <li class="nav-item">
              <router-link to="/about" class="nav-link active"
                >About</router-link
              >
            </li>

            <li class="nav-item dropdown">
              <router-link to="/projects" class="nav-link active">Projects</router-link>
            </li>

            <li class="nav-item dropdown">
              <router-link to="/testimonial" class="nav-link active">Testimonial</router-link>
            </li>

            <li class="nav-item dropdown">
              <router-link to="/resume" class="nav-link active"
                >Resume</router-link
              >
            </li>

            <li class="nav-item dropdown">
              <router-link to="/contact" class="nav-link active"
                >Contact</router-link
              >
            </li>

            
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Modak&display=swap');


  .offcanvas{
    font-size: 40px;
    display: flex;
    background: url(../assets/Imgs/cloud1.png);
    background-size: contain;
    text-decoration-color: azure;
  }

  .offcanvas-title{
    font-family: "Modak", cursive;
    font-size: 50px;
    color: rgb(0, 0, 0);
    -webkit-text-stroke: 3px rgb(0, 255, 238);
  }
</style>