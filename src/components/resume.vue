<template>

  <section id="resumepg ">
    <div class="container" >
      <div class="fixed-half">
        <div class="title">
          <div class="resume_left p-5">
            <div class="resume_profile img-fluid">
              <img src="../assets/Imgs/undecided-removebg-preview.png" id="profile_pic" />
            </div>
            <div class="resume_content">
              <div class="resume_item resume_info">
                <div class="title">
                  <p class="bold">Liam Engel</p>
                  <p class="regular">Designer</p>
                </div>
                <ul>
                  <li>
                    <div class="icon">
                      <i class="fas fa-map-signs"></i>
                    </div>
                    <div class="data">
                      18 Infanta, Cape Town <br />
                      SA
                    </div>
                  </li>
                  <li>
                    <div class="icon">
                      <i class="fas fa-mobile-alt"></i>
                    </div>
                    <div class="data">+27 646514798</div>
                  </li>
                  <li>
                    <div class="icon">
                      <i class="fas fa-envelope"></i>
                    </div>
                    <div class="data">engelliam71@gmail.com</div>
                  </li>
                </ul>
              </div>

              <div class="resume_item resume_social">
                <a href="https://github.com/TOP-FLOOR-BOSS"><i class="bi bi-github" id="socialIcon"></i></a>
                <a href=""><i class="bi bi-linkedin" id="socialIcon"></i></a> 
                <a href="https://youtu.be/L6vm9riiec4"><i class="bi bi-youtube" id="socialIcon"></i></a> 
              </div>
            </div>
          </div>
        </div>
      </div>
          <!-- Right side -->
      <div class="resume_right">
        <div class="resume_item resume_about">
          <div class="title">
            <p class="bold">About my work xp</p>
          </div>
          <p>
            At the moment I am fresh out of school, but before I jpined life choices, I had experience with computers at my highschool. When I matriculated I joined a primary school and Worked there for 4 months as a Student Teacher
          </p>
        </div>
        <div class="resume_item resume_work">
          <div class="title">
            <p class="bold">Work Experience</p>
          </div>
          <ul>
            <li>
              <div class="date">2017 - 2020</div>
              <div class="info">
                <p class="semi-bold">High school</p>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Nostrum, voluptatibus!
                </p>
              </div>
            </li>
            <li>
              <div class="date">2020 - 2021</div>
              <div class="info">
                <p class="semi-bold">Matric Year</p>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Nostrum, voluptatibus!
                </p>
              </div>
            </li>
            <li>
              <div class="date">2021 - Present</div>
              <div class="info">
                <p class="semi-bold">Life Choices</p>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Nostrum, voluptatibus!
                </p>
              </div>
            </li>
          </ul>
        </div>
        <div class="resume_item resume_education">
          <div class="title">
            <p class="bold">Education</p>
          </div>
          <ul>
            <li>
              <div class="date">2009 - 2016</div>
              <div class="info">
                <p class="semi-bold">Muizenburg Primary School</p>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Nostrum, voluptatibus!
                </p>
              </div>
            </li>
            <li>
              <div class="date">2017 - 2022</div>
              <div class="info">
                <p class="semi-bold">Bergvliet Highschool </p>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Nostrum, voluptatibus!
                </p>
              </div>
            </li>
          </ul>
        </div>
        <div class="resume_item resume_hobby">
          <div class="title">
            <p class="bold">Hobby</p>
          </div>
          <ul>
            <li><i class="fa-solid fa-volleyball"></i></li>
            <li><i class="fas fa-gamepad"></i></li>
            <li><i class="fas fa-music"></i></li>
            <li><i class="fa-solid fa-boot-heeled"></i></li>
          </ul>
        </div>
      </div>


    </div>


  </section>
</template>

<script>
export default {};
</script>

<style scoped>
html {
  background-color: #fff !important; 
}

#socialIcon{
  width: 35px;
  height: 35px;
  color: #ffffff;
  border-radius: 50%;
  margin-right: 15px;
  font-size: 30px;

}

#profile_pic {
  width: 230px;
  height: 180px;
  background: rgba(204, 192, 192, 0.4);
}

#resumepg {
  padding: 80px;
  display: inline;
}

.container {
  /* min-height: 100vw; */
  /* height: 100vh; */
}

.fixed-half {
  /* padding: 80px; */
  position: absolute;
  will-change: transform;
  background-color: rgb(18, 129, 249);
  background-size: cover;
  left: 0;
  right: 50%;
  top: 0;
  bottom: 0;
  width: 400px;
  height: 900px;
}
.title {
  display: flex;
  align-items: center;
  padding: 35px;
}

h1 {
  font-size: 54px;
  margin-top: 0;
  text-transform: uppercase;
  color: white;
}

.scrolling-half {
  position: relative;
  width: auto;
  margin-left: 50%;
  color: #333;
  font-size: 18px;
  text-align: justify;
  /* line-height: 1.55; */
}
.wrapper {
  width: 100%;
  padding: 20px 50px;
}

.bold {
  font-family: Iceland;
  font-size: 55px;
  color: white;
  -webkit-text-stroke: 2px rgb(1, 0, 18);
  text-decoration: underline rgb(31, 13, 225) 7px;
}

.semi-bold {
  font-weight: 500;
  font-size: 16px;
}

/* .resume {
  width: 800px;
  height: auto;
  display: flex;
  margin: 50px auto;
} */

.resume_left {
  width: 480px;
}



.resume_left .resume_profile img {
  width: 100%;
  height: 100%;
}

.resume_left .resume_content {
  padding: 0 25px;
}

.title {
  margin-bottom: 20px;
}

.resume_left .bold {
  color: #fff;
}

.resume_left .regular {
  color: #b1eaff;
}

.resume_item {
  padding: 25px 0;
  border-bottom: 2px solid #b1eaff;
}

.resume_left .resume_item:last-child,
.resume_right .resume_item:last-child {
  border-bottom: 0px;
}

.resume_left ul li {
  display: flex;
  margin-bottom: 10px;
  align-items: center;
}

.resume_left ul li:last-child {
  margin-bottom: 0;
}

.resume_left ul li .icon {
  width: 35px;
  height: 35px;
  background: #fff;
  color: #0bb5f4;
  border-radius: 50%;
  margin-right: 15px;
  font-size: 16px;
  position: relative;
}

.icon i,
.resume_right .resume_hobby ul li i {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.resume_left ul li .data {
  color: #b1eaff;
}

.resume_left .resume_skills ul li {
  display: flex;
  margin-bottom: 10px;
  color: #b1eaff;
  justify-content: space-between;
  align-items: center;
}

.resume_left .resume_skills ul li .skill_name {
  width: 25%;
}

.resume_left .resume_skills ul li .skill_progress {
  width: 60%;
  margin: 0 5px;
  height: 5px;
  background: #009fd9;
  position: relative;
}

.resume_left .resume_skills ul li .skill_per {
  width: 15%;
}

.resume_left .resume_skills ul li .skill_progress span {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background: #fff;
}

.resume_left .resume_social .semi-bold {
  color: #fff;
  margin-bottom: 3px;
  
}

.resume_right {
  width: 50%;
  background: rgb(255, 255, 255);
  padding: 25px;
  float: right;
}

 .resume_right .bold {
  color: #0bb5f4;
}

 .resume_right .resume_work ul,
 .resume_right .resume_education ul {
  padding-left: 40px;
  /* overflow: hidden; */
}

.resume_right ul li {
  position: relative;
}

.resume_right ul li .date {
  font-size: 16px;
  font-weight: 500;
  margin-bottom: 15px;
}

.resume_right ul li .info {
  margin-bottom: 20px;
}
/* 
.resume_right ul li:last-child .info {
  margin-bottom: 0;
} */

 .resume_right .resume_work ul li:before,
.resume_right .resume_education ul li:before {
  content: "";
  position: absolute;
  top: 5px;
  left: -25px;
  width: 6px;
  height: 6px;
  border-radius: 50%;
  border: 2px solid #0bb5f4;
}

 .resume_right .resume_work ul li:after,
 .resume_right .resume_education ul li:after {
  content: "";
  position: absolute;
  top: 14px;
  left: -21px;
  width: 2px;
  height: 115px;
  background: #0bb5f4;
}

.resume_right .resume_hobby ul {
  display: flex;
  justify-content: space-between;
}

.resume_right .resume_hobby ul li {
  width: 80px;
  height: 80px;
  border: 2px solid #0bb5f4;
  border-radius: 50%;
  position: relative;
  color: #0bb5f4;
}

 .resume_right .resume_hobby ul li i {
  font-size: 30px;
}

 .resume_right .resume_hobby ul li:before {
  content: "";
  position: absolute;
  top: 40px;
  right: -52px;
  width: 50px;
  height: 2px;
  background: #0bb5f4;
}

 .resume_right .resume_hobby ul li:last-child:before {
  display: none;
}



@media all and (max-width: 795px) {

.fixed-half {
  /* padding: 80px; */
  position: relative;
  width: 400px;
  float: left;
}

#profile_pic {
  width: 130px;
  height: 150px;
  background: rgba(204, 192, 192, 0.4);
}

.resume_left ul li .icon {
  width: 25px;
  height: 25px;
  background: #fff;
  color: #0bb5f4;
  border-radius: 50%;
  margin-right: 15px;
  font-size: 16px;
}


}
</style>