<template>
  <section class="aboutPg vh-100">
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

      <div class="split">
        <div class="row">
          <div class="col">
            <img id="pfp" src="../assets/Imgs/cloud1.png" alt="" />
          </div>

          <div class="col py-3">
            <h2 id="subHeader">Tools that I use</h2>
            <p>
              My motivation to be a Developer started when I was inspirede by
              how technology is such a wide field of options and that
              possibilities are endless. For time being Im only learning, and
              plan to strengthen my skills in all aspects of work that I am
              diving into.
            </p>

            <div class="row py-5">
              <div class="col-lg-6">
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
              <div class="col-lg-6">
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
                    <strong>PhEmailone:</strong>
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

  <section id="skills" class="skills section-bg">
    <div class="container">
      <div class="section-title">
        <h2 id="skillsH">Skills</h2>
        <p>
          Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex
          aliquid fuga eum quidem. Sit sint consectetur velit. Quisquam quos
          quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia
          fugiat sit in iste officiis commodi quidem hic quas.
        </p>
      </div>

      <div class="row skills-content">
        <div class="col-lg-6" >
          
          <p class="fs-2">HTML5 <i class="fa-brands fa-html5"></i></p>
          <div class="progress" style="height: 31px">
            <div
              class="progress-bar 
              bg-success 
              progress-bar-animated
              fs-6"
              
              role="progressbar"
              style="width: 95%"
              aria-valuenow="25"
              aria-valuemin="0"
              aria-valuemax="100"
            >
              95%
            </div>
          </div>

          <!-- <div class="progress">
            <span class="skill">HTML <i class="val">100%</i></span>
            <div class="progress-bar-wrap">
              <div
                class="progress-bar"
                role="progressbar"
                aria-valuenow="100"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
          </div> -->

            <p class="fs-2">CSS <i class="fa-brands fa-css3-alt"></i></p>
            <div class="progress" style="height: 31px" >
              <div
                class="
                  progress-bar
                  bg-primary
                   progress-bar-animated
                   fs-6
                "
                role="progressbar"
                style="width: 75%"
                aria-valuenow="25"
                aria-valuemin="0"
                aria-valuemax="100"
              >
                75%
              </div>
            </div>

            <p class="fs-2">JavaScript <i class="fa-brands fa-java"></i></p>
            <div class="progress" style="height: 31px" >
              <div
                class="
                  progress-bar
                  bg-primary
                   progress-bar-animated
                   fs-6
                "
                role="progressbar"
                style="width: 55%"
                aria-valuenow="25"
                aria-valuemin="0"
                aria-valuemax="100"
              >
                55%
              </div>
            </div>
        </div>

        <!-- End Of first Three rows -->

        <div class="col-lg-6" data-aos="fade-up" data-aos-delay="100">

            <p class="fs-2">MySQL</p>
            <div class="progress" style="height: 31px" >
              <div
                class="
                  progress-bar
                  bg-primary
                 progress-bar-animated
                 fs-6
                "
                role="progressbar"
                style="width: 93%"
                aria-valuenow="25"
                aria-valuemin="0"
                aria-valuemax="100"
              >
                95%
              </div>
            </div>

            <p class="fs-2">Vue.Js</p>
            <div class="progress" style="height: 31px" >
              <div
                class="
                  progress-bar
                  bg-primary
                  progress-bar-animated
                  fs-6
                "
                role="progressbar"
                style="width: 45%"
                aria-valuenow="25"
                aria-valuemin="0"
                aria-valuemax="100"
              >
                45%
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

<style>
.aboutPg {
  padding: 80px;
  background: rgb(18, 129, 249);
  background: radial-gradient(
    circle,
    rgb(197, 230, 230) 10%,
    rgb(0, 191, 255) 77%
  );
}

.abtTitle h2{
    font-family: Iceland;
    font-size: 85px;
    color: white;
  	-webkit-text-stroke: 2px rgb(1, 0, 18);
    text-decoration: underline  rgb(31, 13, 225) 7px;
  }

  #skillsH{
        font-family: Iceland;
    font-size: 85px;
    color: white;
  	-webkit-text-stroke: 2px rgb(1, 0, 18);
    text-decoration: underline  rgb(31, 13, 225) 7px;
  }

#aboutMeheader {
  font-family: Iceland;
  font-size: 90px;
  text-decoration: underline;
}


#subHeader{
  font-size: 49px;
  color: rgb(0, 0, 0);
  -webkit-text-stroke: 1px rgb(255, 189, 22);
    font-family: Iceland;

}
.split {
  padding: 10px;
  font-size: 18px;
  background: rgba(204, 192, 192, 0.2);
  /* height: 100%; */
}

.split ul {
  list-style: none;
  padding: 0;
}
.split ul li {
  margin-bottom: 20px;
  display: flex;
  align-items: center;
}
.split ul strong {
  margin-right: 10px;
}
.split ul i {
  font-size: 16px;
  margin-right: 5px;
  color: #149ddd;
  line-height: 0;
}
.split p:last-child {
  margin-bottom: 0;
}

#pfp {
  border-radius: 8%;
  width: 340px;
  height: 340px;
}

#hovereffect {
  max-width: 50%;
}

/* Skils Section */

#skills{
  padding: 30px;
  background:  rgb(18, 129, 249);
  background: radial-gradient(
    circle,
    rgb(197, 230, 230)  10%,
    rgb(0, 191, 255) 77%
  );;
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

.skills-content p{
    font-family: Iceland;
    font-size: 25px;
    color: rgb(0, 0, 0);
  	-webkit-text-stroke: 1px rgb(255, 189, 22);
}
/* .tooltip{
  cursor: pointer;
  border-bottom: 2px dotted;
  position: relative;
  padding: 7px;
  font-weight: bold;
}


#tooltiptext{
  color: rgb(0, 0, 0);
  position: absolute;
  transform: translateX(-50%);
  white-space: nowrap;
}

#tooltiptext ::before{
  content: "";
  position: absolute;
  transform: translateX(-50%);
} */
</style>