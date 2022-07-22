<template>
  
            <!-- Contact Page -->
        <section class="vh-100 pt-5 d-flex align-bottom" id="contact">
            <div class="container container col text-center" id="Conactpgggg">
                <form action="https://formspree.io/f/xnqwlzbo" method="post" target="_blank">
                  <p> <span class="header2 text-white fs-1">CONTACT  Me</span>  <i class="bi bi-telephone p-3 text-white fs-2"></i></p>
              
              <div class="login">
                <input type="text" placeholder="Your Name" class="input">
                <input type="text" placeholder="Your Email Address" class="input">
              </div>
              
              <div class="subject">
                <input type="text" placeholder="Subject" class="input">
              </div>
              
              <div class="msg">
                <textarea  class="area" placeholder="Leave a Message"></textarea>
              </div>
              
              <div class="Contactbtn">Send Message
  
              </div>
              <br>
              <br>
             
              <p class="header2 fs-4">Follow me</p>
              <br>
              <br>
             
    
    
                 </form>

            </div>

        </section>

</template>

<script>
export default {

}
</script>

<style>

#contact{
  padding: 0px;
  background: linear-gradient(-45deg, #526fee, #c8ffc8, #23a6d5, #23d5ab);
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

.header2{
  font-family: Iceland;
  font-size: 85px;
  color: white;
  -webkit-text-stroke: 2px rgb(1, 0, 18);
  text-decoration: underline rgb(31, 13, 225) 7px;
}

.input,
.msg .area{
  width: 100%;
  padding: 20px;
  box-sizing: border-box;
  margin-bottom: 25px;
  border: 2px solid #e9eaea;
  font-size: 17px;
  border-radius: 5px;
  outline: none;
  transform: all 0.5s ease;
}

.login .input{
  width: 48%;
  float: left;
  margin-right: 4%;
}

.login .input:last-child{
  margin-right: 0;
}

.msg .area{
  height: 200px;
}

.Contactbtn{
  width: 180px;
  background: #486255;
  height: 50px;
  line-height: 50px;
  text-align: center;
  border-radius: 5px;
  margin: 0 auto;
  color: #fff;
  text-transform: uppercase;
  cursor: pointer;
}

.input:focus,
.msg .area:focus{
  border: 2px solid #486255;
}

::-webkit-input-placeholder{
  font-family: 'roboto';
}


</style>