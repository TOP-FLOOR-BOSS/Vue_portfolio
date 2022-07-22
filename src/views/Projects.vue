<template>
  <section class="projects">
    <h1>Project</h1>

    <!-- Button trigger modal -->
<div class="container">
  <div class="row">

    <div class="card m-3 mx-auto" v-for="(project, index) in projects">
      <button
        type="button"
        class="btn btn-primary"
        data-bs-toggle="modal"
        :data-bs-target="'#exampleModal'+index"
      >
        <img id="modalIMG" class="img-fluid" :src="project.image">
      </button>

      <!-- Modal -->
      <div
        class="modal fade"
        :id="'exampleModal'+index"
        tabindex="-1"
        aria-labelledby="exampleModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title" id="exampleModalLabel">{{project.title}}</h5>
              <button
                type="button"
                class="btn-close"
                data-bs-dismiss="modal"
                aria-label="Close"
              ></button>
            </div>
            <div class="modal-body">{{ project.id }}</div>
            <div class="modal-footer">
              <button
                type="button"
                class="btn btn-secondary"
                data-bs-dismiss="modal"
              >
                Close
              </button>
              <button type="button" class="btn btn-primary">
               <a href={{project.title}}><i class="bi bi-github" id="socialIcon"></i></a> 
              </button>
            </div>
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
          id: "In this project I created a to do list that creates,deletes and Edits",
          image: "https://i.postimg.cc/BvHgRHxH/To-Do-list.png",
          title: "To-Do list",
          netlify: "",
        },
        {
          id: "This is a claculator that I created with JavaScript",
          image: "https://i.postimg.cc/c4MSwxXc/Calculator.png",
          title: "Calculator",
          netlify: "",
        },
        {
          id: "This is a Real Estate Website that can filter and sort by country and name ",
          image: "https://i.postimg.cc/QdJd8g2h/Property-listing.png",
          title: "Property List",
          netlify: "",
        },
        {
          id: "This project calculates the are of a Triangle",
          image: "https://i.postimg.cc/mDNwV5qK/Area-of-Triangle.png",
          title: "Area Of Triangle",
          netlify: "",
        },
        {
          id: "This is apersonal portfolio that i used using bootstrap",
          image: "https://i.postimg.cc/Jnm3yQnx/Bootsrap-portfolio.png",
          title: "Bootsrap Portfolio",
          netlify: "",
        },
        {
          id: "This converts minutes to seconds",
          image: "https://i.postimg.cc/cLSfkm7S/convert-minutes-to-Secs.png",
          title: "Convert Minutes to Second",
          netlify: "",
        },
      ],
    };
  },
};
</script>

<style>




.projects {
  padding: 80px;
  background: linear-gradient(-45deg, #526fee, #c8ffc8, #23a6d5, #23d5ab);
  background-size: 400% 400%;
  animation: gradient 15s ease infinite;
  height: auto;
  min-height: 100vh;
  
}

.card {
 width: 350px;
}

#socialIcon{
  width: 20px;
  height: 20px;
  color: #ffffff;
  font-size: 20px;

}

@keyframes gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

.projects h1 {
  font-family: Iceland;
  font-size: 85px;
  color: white;
  -webkit-text-stroke: 2px rgb(1, 0, 18);
  text-decoration: underline rgb(31, 13, 225) 7px;
}
#modalIMG {
  width: 370px;
  height: 200px;
  object-fit: cover;
}

@media all and (max-width: 499px) {
  .projects button {
    width: 200px;
  }

  #modalIMG {
    width: 170px;
    height: 200px;
  }

  .projects h1 {
    font-size: 60px;
  }
}
</style>