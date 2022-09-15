<template>
  <section class="projects">
    <h1 class="P1">Projects</h1>

    <!-- Button trigger modal -->
    <div class="row col-md-6 d-flex justify-content-center pt-5">
      <div class="slide-up" v-for="(project, index) in projects" :key="project">
        <button
        class="buttonStyle"
          type="button"
          data-bs-toggle="modal"
          :data-bs-target="'#exampleModal' + index"
        >
          <div class="container">
            <div class="card">
              <img id="modalIMG" class="img-fluid" :src="project.image" />
              <h2 class="card__title">{{ project.title }}</h2>
              <ul>
                <li class="selected"></li>
                <li></li>
                <li></li>
              </ul>
            </div>
          </div>
        </button>            
        
        <div class="gify">
              <img src="../assets/Imgs/gwaves.gif" alt="" />
            </div>

        <!-- Modal -->
        <div
          class="modal fade"
          :id="'exampleModal' + index"
          tabindex="-1"
          aria-labelledby="exampleModalLabel"
          aria-hidden="true"
        >
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="modalT">
                  {{ project.title }}
                </h5>
                <button
                  type="button"
                  class="btn-close"
                  data-bs-dismiss="modal"
                  aria-label="Close"
                ></button>
              </div>
              <div id="desc" class="modal-body">{{ project.id }}</div>
              <div class="modal-footer">
                <button
                  type="button"
                  class="btn btn-secondary"
                  data-bs-dismiss="modal"
                >
                  Close
                </button>
                <button type="button" class="btn btn-primary">
                  <a href="{{project.title}}"
                    ><i class="bi bi-github" id="socialIcon"><a href="{{project.netlify}}"></a></i
                  ></a>
                </button>
              </div>
            </div>

          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
// import { url } from 'inspector';

export default {
  data() {
    return {
      projects: [     
        
      {
          id: "My final assesment, for the year mark, an e-comerce bussines that sells art",
          image: "https://i.postimg.cc/xTwr9sj7/Screenshot-2022-09-15-153607.png",
          title: "Injured Generation",
          netlify: "https://comforting-cat-b51b1b.netlify.app",
        },
        {
          id: "In this project I created a to do list that creates,deletes and Edits",
          image: "https://i.postimg.cc/BvHgRHxH/To-Do-list.png",
          title: "To-Do list",
          netlify: "https://wondrous-profiterole-c7fee8.netlify.app",
        },
        {
          id: "This is a claculator that I created with JavaScript",
          image: "https://i.postimg.cc/c4MSwxXc/Calculator.png",
          title: "Calculator",
          netlify: "https://harmonious-chaja-901d18.netlify.app",
        },
        {
          id: "This is a Real Estate Website that can filter and sort by country and name ",
          image: "https://i.postimg.cc/QdJd8g2h/Property-listing.png",
          title: "Property List",
          netlify: "https://zingy-kulfi-06f25e.netlify.app",
        },
  
        {
          id: "This is a personal portfolio that i used using bootstrap",
          image: "https://i.postimg.cc/Jnm3yQnx/Bootsrap-portfolio.png",
          title: "Bootsrap Portfolio",
          netlify: "https://liamengelsportfolio.netlify.app",
        },
        {
          id: "This converts minutes to seconds",
          image: "https://i.postimg.cc/cLSfkm7S/convert-minutes-to-Secs.png",
          title: "Convert Minutes to Second",
          netlify: "https://heartfelt-gingersnap-38a5df.netlify.app",
        },
      ],
    };
  },
};
</script>

<style scoped>


@import url('https://fonts.googleapis.com/css2?family=Modak&display=swap');


.P1 {
  font-family: "Modak", cursive;
  font-size: 85px;
  color: rgb(145, 14, 155);
  -webkit-text-stroke: 2px rgb(0, 255, 13);
  text-decoration: underline rgb(31, 13, 225) 7px;
}

.buttonStyle{
  background: #0077ff;
  backface-visibility: hidden;
  height: 150px;
}

.gify {
  display: flex;
  float: right;
  padding-bottom: 220px;
}
.projects {
  padding: 80px;
  background: linear-gradient(-45deg, #526fee, #ffc8f5, #23a6d5, #8b23d5);
  animation: gradient 15s ease infinite;
  height: auto;
}

#socialIcon{
 color:  white;
}

#desc{
  font-size: 18px;
  color: black;
  font-weight: 700;
}

#modalT{
  font-family: 'Modak', cursive;  
  font-size:30px;
}
.slide-up {
  display: flex;
  
}

#modalIMG{
  width:790px;
  height: 500px;
}

.container .card {
  text-align: center;
  background: linear-gradient(-45deg, #526fee, #ffc8f5, #23a6d5, #8b23d5);
  animation: gradient 15s ease infinite;
  height: 20px;
  padding: 20px;
  width: 630px;
  border-radius: 5px;
  box-shadow: 0px 5px 20px rgba(0, 0, 0, 0.2);
  transition: all 0.3s ease;
}

.card:hover {
  box-shadow: 0px 5px 20px rgba(0, 0, 0, 0.4);
  z-index: 99;
  transform: scale(1.2);
}

.card:nth-child(2) {
  transform: scale(1.1);
  z-index: 1;
}
.card__title {
  font-size: 32px;
  color: #000000;
  -webkit-text-stroke: 1px rgb(255, 0, 153);
  background: white;
  font-family: sans-serif;
}
.card_text {
  color: #cfd6de;
  font-family: sans-serif;
}
.card ul,
.card li {
  list-style: none;
  padding: 0;
  margin: 0;
}

.card li {
  background: #0077ff;
  height: 5px;
  width: 5px;
  border-radius: 50%;
  margin: 0px 7px;
}
.card li.selected {
  background-color: #547190;
}
.card a {
  text-decoration: none;
  color: #000;
  position: absolute;
  right: 50px;
  top: 10px;
}
.card a::before {
  display: block;
}

.card ul {
  display: flex;
  margin: 0 auto;
  justify-content: center;
}

.card__img {
  border: 4px solid #547190;
  border-radius: 50%;
  display: flex;
}
</style>