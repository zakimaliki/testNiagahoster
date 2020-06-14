<template>
  <div class="w-100 border-bottom">
    <div class="row">
      <div class="col-md-12 pb-2">
        <nav class="navbar navbar-expand-md navbar-light p-0">
          <div class="container">
            <img
              src="../assets/svg/label.svg"
              width="30"
              height="30"
              class="d-inline-block align-top p-0 mr-2 labeltop"
              alt
            />
            <p class="my-0">Gratis Ebook 9 Cara Cerdas Menggunahkan Domain [x]</p>
            <ul class="navbar-nav ml-auto">
              <li class="nav-item">
                <a class="nav-link" href="#">
                  <i class="fa d-inline fas fa-phone"></i>&nbsp;0274-5305505
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">
                  <i class="fa d-inline fa-comments"></i>&nbsp;LIve
                  chat
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">
                  <i class="fa d-inline fas fa-user-circle"></i>&nbsp;Member Area
                </a>
              </li>
            </ul>
          </div>
        </nav>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Topbar",
  props: {
    msg: String
  }
};
</script>

<style scoped>
.labeltop {
  margin-top: -10px;
}

@media (max-width: 767.98px) {
  .navbar-expand-md > .container,
  .navbar-expand-md > .container-fluid {
    padding-right: 62px;
    padding-left: 0px;
  }
}
</style>


