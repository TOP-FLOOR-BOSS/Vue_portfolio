<template>

<section class="footer bg-dark">
  <footer id="footer">

    <div class="bottom-0 footer-custom" id="footer-custom">
      <div class="copyright">
        &copy; Copyright <strong><span>Liams Prtfolio</span></strong>
      </div>
      <div class="credits">

        Designed by Liam Engel <a href="https://bootstrapmade.com/">BootstrapMade</a>
      </div>
    </div>

  </footer>
</section>
</template>
<script>
export default {
}
</script>
<style scoped>

#footer {
  padding: 15px;
  color: #f4f6fd;
  font-size: 14px;
  /* position: absolute; */
  flex-direction: column;
  display: flex;
  left: 0;
  bottom: 0;
  margin-top:auto ;
  width: 100%;
  z-index: 99;
  background: #040b14;
}

#footer-custom{
  padding:0 0 30px 0;
  /* bottom: 100px; */
}

#footer .copyright {
  text-align: center;
}
#footer .credits {
  padding-top: 5px;
  text-align: center;
  font-size: 13px;
  color: #eaebf0;
}
@media (max-width: 1199px) {
  #footer {
    position: static;
    width: auto;
    padding-right: 20px 15px;
  }
}

</style>