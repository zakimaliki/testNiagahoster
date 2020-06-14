<template>
  <div class="container">
    <div class="row">
      <div class="py-5 pi-draggable">
        <div class="container">
          <div class="row">
            <div
              class="px-md-5 p-3 col-md-6 d-flex flex-column align-items-start justify-content-center"
            >
              <h2>Linux Teknologi yang Stabil dengan Tekologi LVE</h2>
              <div class="row">
                <div class="col-md-12 p-1" style>
                  <p>
                    SuperMicro
                    <b class="Call5">Xeon 24-Cores</b> server dengan
                    <b class="Call5">128 GB</b> dan teknologi
                    <b class="Call5">LIVE CloudLInux</b> untuk stabil server
                    Anda. Dilengkapi dengan
                    <b class="Call5">SSD</b> untuk kecepatan
                    <b class="Call5">MySQL</b> dan caching, Apache oad balencer berbasis
                    LiteSpeed Teknologies,
                    <b class="Call5">CageFS</b> security,
                    <b class="Call5">Raid-10</b> dan backup untuk kemanan website PHP Anda.
                  </p>
                </div>
                <a href="#">
                  <img src="../assets/svg/Group6.svg" alt />
                </a>
              </div>
            </div>
            <div class="col-md-6">
              <img class="img-fluid d-block" src="../assets/images/Image support.png" width="503" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Spesificationserver",
  props: {
    msg: String
  }
};
</script>
<style scoped>
.Call5 {
  font-weight: bold !important;
}
</style>

