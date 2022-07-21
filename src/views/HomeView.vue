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

     <button >
      <span class="downcircle"> <i class="fa-solid fa-circle-down"></i> </span>
     </button>

    </div>



</div>

<section class="home2 vh-100">

      <div id="text-changer-1" class="content">
        <h1 id="aspiring" >I am an aspiring <br><span class="glow">......Web-Developer</span> </h1>
        <p>
              I aspire to become a full-stack Web-Developer, at the moment I'am working on sharpening my skills and becoming fluent in all coding languages. I enjoy creating websites of all sort, so enjoy my portfolio 
              
        </p>
        <br>
      </div>

      <a href="#about">
        <button id="abtMebtn" type="button" class="btn btn-outline-light btn-lg">About Me</button>
      </a>



</section>



<!-- 
    <About id="about" /> -->


 
</template>

<script>
// @ is an alias to /src

import About  from "./AboutPage.vue"
// import second from "../views/AboutPage.vue#2nd"
export default {
  components: {
    About
  }

};



</script>

<style>


#aspiring{
  font-size: 50px;
  
}

.btn{
position:relative;
top: 19%;

}

#text-changer-1{
  max-width:750px;  
  margin-left:75px;
  font-family: 'Inconsolata', monospace;
font-family: 'Kanit', sans-serif;
  font-size: 20px;
  color: rgb(241, 216, 216)}


.grid-container {
  display: grid;
  grid-template-columns: auto auto auto;
  background-color: #2196F3;
  padding: 10px;
  }


	#arrow {
    	height:600px;
      
    }
    
    .downcircle {
    	position:absolute;
      bottom:0px;
      font-size: 80px;


    }

.glow{
  font-size: 77px;
  font-family: Iceland;
  animation: neon2 1.5s ease-in-out infinite alternate;
}

/* @keyframes neon2 {
  from {
    text-shadow: 0 0 10px rgb(44, 6, 6), 0 0 20px rgb(47, 9, 9), 0 0 30px #fff, 0 0 40px #228dff,
      0 0 70px #22deff, 0 0 80px #228dff, 0 0 100px #228dff, 0 0 150px #228dff;
  }

}; */

    .home2{
      padding: 80px;
     background: 
    /* bottom, image */ url(../assets/Imgs/clear-concept-underwater-ocean-floor-perspectives-shutterstock-1422884786-900x506.jpg);
  background-size :cover;
  background-attachment: fixed;

    }

#landing{

  height:100vh;
  background:url(../assets/Imgs/clouds_sky_bridge_people_reflection_sea_92817_1920x1080.jpg) no-repeat center center fixed;
  background-size:cover;
  -webkit-background-size:cover;
  -o-background-size:cover;
  -moz-background-size:cover;
}


/* Text animation */

a:hover,a:focus{text-decoration:none;}
.svg-wrapper {
  position: relative;
  top: 35%;
  transform: translateY(-40%);
	margin: 0 auto;
  width: 320px;
  max-height:60px;
  cursor:default;

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
  text-align:center;
}
.svg-wrapper:hover .shape {
  stroke-width: 2px;
  stroke-dashoffset: 0;
  stroke-dasharray: 760;
}
/* end cool name effect */
#port-wrapper{
  width:100%;height:100%;
  background:rgba(171, 0, 0, 0.3);
  position:absolute;
}
.text-2 h2{
  font-family: 'Josefin Slab', serif;
  font-size: 20px;
}

button:hover, button:focus{
  background:rgba(0,0,0,0.4);
  outline:none;
}
.content{
  margin:50px;
  margin-top:75px;
  margin-bottom:0;
}
@media only screen and (max-width : 768px){
  #text-changer-1{
    margin-left:50px;
  }
}

#text-changer-1 img{
  margin:-10px 10px 5px 0;
  border-radius:50px;
}
#text-changer-3 .social{
  margin:35px;
}
#text-changer-3 .fa{
  margin:5px;
  color:#fff;
}
#text-changer-3 .fa:hover{
  color:#2e8ece;
}
.project{
  height:100%; width:100%;
  border:1px solid #fff;
  margin-bottom:5px;
}
#text-changer-2{
  text-align:center;
  height:100%;
}

#abtMebtn{

  height: 100px;
  width: 300px;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  font: 1.5rem sans-serif;
  cursor: pointer;
  will-change: transform;
}

#abtMebtn::before,
#abtMebtn::after {
  position: absolute;
  top: 0;
  left: 0;
  content: '';
  display: block;
  background-color: deeppink;
  transition: all 250ms ease-in-out;
}

#abtMebtn::before {
  width: 2px;
  height: 100px;
  box-shadow: 298px 0 deeppink;
}

#abtMebtn::after {
  height: 2px;
  width: 300px;
  box-shadow: 0 98px deeppink;
}

#abtMebtn:hover::before {
  left: -10px;
  box-shadow: 318px 0 deeppink;
}

#abtMebtn:hover::after {
  top: -10px;
  box-shadow: 0 118px deeppink;
}

</style>
