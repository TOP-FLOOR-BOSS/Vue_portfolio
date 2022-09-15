<template>
  <div id="landing">
    <div class="svg-wrapper">
      <a id="jump" href="#portfolio">
        <svg height="60" width="320" xmlns="http://www.w3.org/2000/svg">
          <rect class="shape" height="60" width="320" />
          <div class="text">Liam Engel</div>
        </svg>
      </a>
    </div>

    <div id="arrow">
      <button>
        <span class="downcircle">
      <div class="scroll-down"></div>        
      </span>
      </button>
    </div>
  </div>

  <section class="home2 vh-100">
    <div class="container">
      <div id="homept2">
        <h1 id="aspiring">
          I am an aspiring <br /><span class="glow">......Web-Developer</span>
        </h1>
        <p>
          I aspire to become a full-stack Web-Developer, at the moment I'am
          working on sharpening my skills and becoming fluent in all coding
          languages. I enjoy creating websites of all sort, so enjoy my
          portfolio
        </p>
        <br />
      </div>

      <a href="#about">
        <button
          id="abtMebtn"
          type="button"
          class="btn btn-outline-light btn-lg"
        >
          About Me
        </button>
      </a>
    </div>
  </section>

  <!-- 
    <About id="about" /> -->
</template>

<script>

</script>

<style scoped>
#aspiring {
  font-size: 50px;
}

.btn {
  position: relative;
  top: 19%;
}

.home2 {
  padding: 80px;
  background: 
    /* bottom, image */ url(../assets/Imgs/clear-concept-underwater-ocean-floor-perspectives-shutterstock-1422884786-900x506.jpg);
  background-size: cover;
  background-attachment: fixed;
}

#homept2{
  max-width: 750px;
  margin-left: 75px;
  font-family: "Inconsolata", monospace;
  font-family: "Kanit", sans-serif;
  font-size: 20px;
  color: rgb(241, 216, 216);
}

.grid-container {
  display: grid;
  grid-template-columns: auto auto auto;
  background-color: #2196f3;
  padding: 10px;
}

#arrow {
  height: 600px;
}

.downcircle {
  position: absolute;
  bottom: 0px;
  font-size: 80px;
}

.glow {
  font-size: 77px;
  font-family: Iceland;
  animation: neon2 1.5s ease-in-out infinite alternate;
}





#landing {
  height: 100vh;
  background: url(../assets/Imgs/clouds_sky_bridge_people_reflection_sea_92817_1920x1080.jpg)
    no-repeat center center fixed;
  background-size: cover;
  -webkit-background-size: cover;
  -o-background-size: cover;
  -moz-background-size: cover;
}

/* Text animation */

a:hover,
a:focus {
  text-decoration: none;
}
.svg-wrapper {
  position: relative;
  top: 35%;
  transform: translateY(-40%);
  margin: 0 auto;
  width: 320px;
  max-height: 60px;
  cursor: default;
}
.shape {
  stroke-dasharray: 140 540;
  stroke-dashoffset: -474;
  stroke-width: 8px;
  fill: transparent;
  /* modify this with the color you want */
  stroke: #1509bc;
  border-bottom: 5px solid black;
  transition: stroke-width 1s, stroke-dashoffset 1s, stroke-dasharray 1s;
}
.text {
  font-family: Iceland;
  font-size: 52px;
  line-height: 32px;
  letter-spacing: 9px;
  color: rgb(0, 0, 0);
  top: -48px;
  position: relative;
  text-align: center;
}
.svg-wrapper:hover .shape {
  stroke-width: 2px;
  stroke-dashoffset: 0;
  stroke-dasharray: 760;
}
/* end cool name effect */
#port-wrapper {
  width: 100%;
  height: 100%;
  background: rgba(171, 0, 0, 0.3);
  position: absolute;
}
.text-2 h2 {
  font-family: "Josefin Slab", serif;
  font-size: 20px;
}

button:hover,
button:focus {
  background: rgba(0, 0, 0, 0.4);
  outline: none;
}
/* .content{
  margin:50px;
  margin-top:75px;
  margin-bottom:0;
} */
@media only screen and (max-width: 768px) {
  #text-changer-1 {
    margin-left: 50px;
  }
}

/* Scroll */


.scroll-down {
  height: 80px;
  width: 40px;
  border: 2px solid black;
  position: absolute;
  left: 50%;
  bottom: 20px;
  border-radius: 50px;
  cursor: pointer;
}
.scroll-down::before,
.scroll-down::after {
  content: "";
  position: absolute;
  top: 20%;
  left: 50%;
  height: 10px;
  width: 10px;
  transform: translate(-50%, -100%) rotate(45deg);
  border: 2px solid black;
  border-top: transparent;
  border-left: transparent;
  animation: scroll-down 1s ease-in-out infinite;
}
.scroll-down::before {
  top: 30%;
  animation-delay: 0.3s;
  /* animation: scroll-down 1s ease-in-out infinite; */
}

@keyframes scroll-down {
  0% {
    /* top:20%; */
    opacity: 0;
  }
  30% {
    opacity: 1;
  }
  60% {
    opacity: 1;
  }
  100% {
    top: 90%;
    opacity: 0;
  }
}




#text-changer-3 .social {
  margin: 35px;
}
#text-changer-3 .fa {
  margin: 5px;
  color: #fff;
}
#text-changer-3 .fa:hover {
  color: #2e8ece;
}
.project {
  height: 100%;
  width: 100%;
  border: 1px solid #fff;
  margin-bottom: 5px;
}
#text-changer-2 {
  text-align: center;
  height: 100%;
}

#abtMebtn {
  height: 100px;
  width: 300px;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  font: 1.5rem sans-serif;
  will-change: transform;
  text-decoration: none;
}

#abtMebtn::before,
#abtMebtn::after {
  position: absolute;
  top: 0;
  left: 0;
  content: "";
  display: block;
  background-color: rgb(255, 20, 20);
  transition: all 250ms ease-in-out;
}

#abtMebtn::before {
  width: 4px;
  height: 100px;
  box-shadow: 298px 0 rgb(255, 20, 20);
}

#abtMebtn::after {
  height: 2px;
  width: 300px;
  box-shadow: 0 98px rgb(255, 20, 20);
}

#abtMebtn:hover::before {
  left: -10px;
  box-shadow: 318px 0  rgb(255, 239, 20);
}

#abtMebtn:hover::after {
  top: -10px;
  box-shadow: 0 118px rgb(255, 239, 20);
}

@media all and (max-width: 637px) {

  .homept2{
    padding: 0px;
  }
  #aspiring {
    font-size: 20px;
  }
  #aspiring .glow {
    font-size: 32px;
  }

  #homept2 p{
    font-size: 10px;
  }

  #abtMebtn{
    height: 80px;
    width: 200px;
  }

#abtMebtn::before {
    box-shadow: 200px 0 deeppink;
      height: 80px;

  }

  #abtMebtn::after {
  height: 2px;
  width: 200px;
  box-shadow: 0 80px deeppink;
}

  .svg-wrapper {
    width: 300px;
  }

}
</style>
