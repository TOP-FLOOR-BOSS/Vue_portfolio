<template>

<section class="testimonial testimonialpg">  
    
    <div class="container text-center">
    <div class="row">
      <!-- <div class="col"> -->
        <div class="card m-3 mx-auto" style="width: 18rem"  v-for="(testimonials, index) in testimonials" :key="index">
          <img :src="testimonials.image" class="testimg img-fluid" />
          <div class="card-body">
            <h3>{{testimonials.title}}</h3>
            <p class="card-text">
              {{testimonials.paragraph}}
            </p>
          </div>
        </div>
      <!-- </div> -->
      </div>
  </div>
  



  
  </section>


</template>

<script>
export default {
  name: 'Testimonial',
  data() {
    return {
      testimonials: [
        {
          image: "https://i.postimg.cc/3JxzgBsg/joel2-1.jpg",
          title: "Joel- Lectturer",
          paragraph:"From my collaboration with him in class, I can conclude that Liam has a desire to work in the coding environment. You will benefit greatly from having him on your team. - Joel Mukanya-Coding Lecturer"
        },
        {
          image: "https://i.postimg.cc/c15xVrBG/Daniel-1.jpg",
          title: "Daniel Fredricks",
          paragraph:"From my collaboration with him in class, I can conclude that Liam has a desire to work in the coding environment. You will benefit greatly from having him on your team."
        },
        {
          image: "https://i.postimg.cc/tJ4Dx9rF/Copy-of-Rasheedah-2.jpg",
          title: "Rasheedah Anhuizen",
          paragraph:"Liam is very ambitious and has that eye for good design. He is always willing and ready to assist his peers ."
        },
        {
          image: "https://i.postimg.cc/W19zQqvq/Snapchat-1887559217.jpg",
          title: "Joshua Solomons",
          paragraph:"Liam is a hard working guy that always does his work to the best of he's abilities and the work produced is no less then amazing and well worked on, he is a very soft spoken person but no doubt you would be very lucky to work with such an awesome guy."
        },
        {
          image: "https://i.postimg.cc/rpWqBkNG/Meagan-2.jpg",
          title: "Meagan William",
          paragraph:"I've witness how determined and hardworking Liam is. He always give his best, always ready to set out to achieve his goals through perseverance and determination. He would be a great asset to any business or company."
        },
        {
          image: "https://i.postimg.cc/GmRmj6j4/Yaseen-1.jpg",
          title: "Yassen Jattiem",
          paragraph:"Yaseen is a person with great potential.I believe that he will be able to accomplish much and that he will be an asset to any company."

        },
      ],
    };
  },
};
</script>

<style>

.testimonialpg{
  padding: 80px;
  background: linear-gradient(-45deg, #526fee, #c8ffc8, #23a6d5, #23d5ab);
  background-size: 400% 400%;
  min-height: 100vh;
  animation: gradient 15s ease infinite;
}

.testimg{
  width: 100%;
  height: 250px;
  object-fit: cover;
  object-position: 0 0;
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
</style>