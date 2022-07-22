<template>
  
        <div class="col">
          <button
            type="button"
            class="btn btn-primary"
            data-bs-toggle="modal"
            data-bs-target="#staticBackdrop"
          >
            <img
              src="../assets/Imgs/convert_minutes_toSecs.png"
              id="modalIMG"
              alt=""
            />
          </button>

          <!-- Modal -->
          <div
            v-for="modal in projects"
            class="modal fade"
            id="staticBackdrop"
            data-bs-backdrop="static"
            data-bs-keyboard="false"
            tabindex="-1"
            aria-labelledby="staticBackdropLabel"
            aria-hidden="true"
          >
            <div class="modal-dialog">
              <div class="modal-content">
                <div class="modal-header">
                  <h5 class="modal-title" id="staticBackdropLabel">
                    Minutes to seconds
                  </h5>
                  <button
                    type="button"
                    class="btn-close"
                    data-bs-dismiss="modal"
                    aria-label="Close"
                  ></button>
                </div>
                <div class="modal-body">Converting minutes into seconds. This project consists of converting minutes to seconds</div>
                <div class="modal-footer">
                  <button
                    type="button"
                    class="btn btn-secondary"
                    data-bs-dismiss="modal"
                  >
                    Close
                  </button>
                  <button type="button" class="btn btn-primary">
                    <i class="bi bi-github" id="socialIcon"></i>
                  </button>
                </div>
              </div>
            </div>          
          </div>
        </div>

</template>

<script>
export default {

}
</script>

<style>

</style>