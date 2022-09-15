<template>
  <section class="aboutPg vh-100 mh-100">
    <!-- <div>
      <h1 id="aboutMeheader">About me</h1>
    </div> -->

    <div class="container">
      <div class="abtTitle m-3">
        <h2>About</h2>
        <p>
          I am somome who always stands on their word when I make any promise,
          this applies to my work aswell, as soon as I start anything I will be
          determined to finish it to my best ability. I dont always have the
          work ethic on everyday but when it comes to due dates i make sure that
          I deliver at any rate and by all means necessary.
        </p>
      </div>

      <div class="container text-center">
        <div class="row">
          <div class="col img-fluid">
            <img
              id="pfp"
              src="../assets/Imgs/undecided-removebg-preview.png"
              alt=""
            />
          </div>
          <div class="col" id="toolslist">
            <h2 id="subHeader"> Info </h2>
            <p>
              My motivation to be a Developer started when I was inspirede by
              how technology is such a wide field of options and that
              possibilities are endless. For time being Im only learning, and
              plan to strengthen my skills in all aspects of work that I am
              diving into.
            </p>

            <div class="row">
              <div class="col">
                <ul>
                  <li>
                    <i class="fa-solid fa-circle-chevron-right"></i>
                    <strong>Birthday:</strong> <span>21 October 2003</span>
                  </li>
                  <li>
                    <i class="fa-solid fa-circle-chevron-right"></i>
                    <strong>Website:</strong> <span>www.example.com</span>
                  </li>
                  <li>
                    <i class="fa-solid fa-circle-chevron-right"></i>
                    <strong>Phone:</strong>
                    <span>+27 64 651 4798</span>
                  </li>
                  <li>
                    <i class="fa-solid fa-circle-chevron-right"></i>
                    <strong>City:</strong>
                    <span>Cape Town, SA</span>
                  </li>
                </ul>
              </div>

              <div class="col">
                <ul>
                  <li>
                    <i class="fa-solid fa-circle-chevron-right"></i>
                    <strong>Age:</strong>
                    <span>18</span>
                  </li>
                  <li>
                    <i class="fa-solid fa-circle-chevron-right"></i>
                    <strong>Degree:</strong> <span>None</span>
                  </li>
                  <li>
                    <i class="fa-solid fa-circle-chevron-right"></i>
                    <strong>Email:</strong>
                    <span>engelliam71@gmail.com</span>
                  </li>
                  <li>
                    <i class="fa-solid fa-circle-chevron-right"></i>
                    <strong>Freelance:</strong> <span>Available</span>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


</template>

<script>
export default {
  methods: {},
};
</script>

<style scoped>
  

  @import url('https://fonts.googleapis.com/css2?family=Modak&display=swap');

.aboutPg {
  /* padding: 80px; */
  background: linear-gradient(-45deg, #4760d1, #00f2ff, #000b61, #00ffbb);
  background-size: 400% 400%;
  animation: gradient 15s ease infinite;
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



.abtTitle h2 {
  font-family: 'Modak', cursive;  
  font-size: 85px;
  color: rgb(145, 14, 155);
    -webkit-text-stroke: 2px rgb(0, 255, 13);
  text-decoration: underline rgb(31, 13, 225) 7px;
  padding: 40px 0 0 0;
}
.abtTitle p {
  font-family: "Kanit", sans-serif;
  -webkit-text-stroke: 0.8px rgb(106, 126, 5);

  font-size: 24px;
  color: white;
}

.progress-bar {
  border-radius: 17px;
}

#subHeader {
  
  font-size: 59px;
  color: rgb(145, 14, 155);
  font-family: 'Modak', cursive;
  -webkit-text-stroke: 2px rgb(0, 255, 13);

  
}
.split {
  padding: 10px;
  font-size: 18px;
  font-family: "Kanit", sans-serif;
  background: rgba(204, 192, 192, 0.2);
  /* height: 100%; */
}

#toolslist p {
  color: white;
  -webkit-text-stroke: 0.8px rgb(126, 5, 5);
  font-family: "Kanit", sans-serif;
  font-size: 25px;
}

#toolslist ul {
  list-style: none;
  padding: 0;
  color: white;
}
#toolslist ul li {
  margin-bottom: 20px;
  display: flex;
  font-size: 16px;
  align-items: center;
}
#toolslist ul strong {
  margin-right: 10px;
}
#toolslist ul i {
  font-size: 26px;
  margin-right: 5px;
  color: #ffffff;
  line-height: 0;
}
#toolslist p:last-child {
  margin-bottom: 0;
}

#pfp {
  border-radius: 4%;
  width: 440px;
  height: 400px;

  margin-right: 90px;
}

#hovereffect {
  max-width: 50%;
}

/* Skils Section */

.section-title {
  color: white;
  font-family: "Kanit", sans-serif;
  font-size: 20px;
}

.skills {
  padding: 80px;
  display: flex;
  background: linear-gradient(-45deg, #eec752, #006d73, #ffffff, #2f453f);
  background-size: 400% 400%;
  animation: gradient 15s ease infinite;
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

#skillsH {
  font-family: Iceland;
  font-size: 85px;
  color: white;
  -webkit-text-stroke: 2px rgb(1, 0, 18);
  text-decoration: underline rgb(31, 13, 225) 7px;
}

.skills .progress {
  height: 60px;
  display: block;
  background: none;
  border-radius: 0;
}
.skills .progress .skill {
  padding: 0;
  margin: 0 0 6px 0;
  text-transform: uppercase;
  display: block;
  font-weight: 600;
  font-family: "Poppins", sans-serif;
  color: #050d18;
}
.skills .progress .skill .val {
  float: right;
  font-style: normal;
}
.skills .progress-bar-wrap {
  background: #dce8f8;
  height: 10px;
}
.skills .progress-bar {
  width: 1px;
  height: 50px;
  transition: 0.9s;
  background-color: #ffffff;
}

.skills-content p {
  font-family: Iceland;
  font-size: 25px;
  color: rgb(0, 0, 0);
  -webkit-text-stroke: 1px rgb(255, 189, 22);
}

.skills-content {
  background: rgba(255, 255, 255, 0.4);
}

@media all and (max-width: 987px) {
  #pfp {
    height: 150px;
    width: 150px;
  }

  .abtTitle p {
    font-family: "Kanit", sans-serif;
    font-size: 10px;
    color: white;
    padding: 0px;
  }

  .abtTitle h2 {
    font-family: Iceland;
    font-size: 55px;
  }

  #subHeader {
    font-size: 39px;
    padding: 0px;
  }

  #toolslist p {
    font-size: 10px;
    padding: 0px;
  }

  #toolslist ul {
    font-size: 10px;
  }

  #skillsH {
    font-family: Iceland;
    font-size: 55px;
  }

  .section-title {
    font-size: 10px;
    padding: 0px;
  }

  .skills-content {
    font-family: Iceland;
    font-size: 20px;
  }
}
</style>