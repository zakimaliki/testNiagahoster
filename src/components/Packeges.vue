<template>
  <div class="container">
    <div class="container">
      <div class="row">
        <div class="text-center mx-auto col-md-12">
          <h1 class="pt-3 pb-4">
            <b>Semua Paket Hosting Sudah Termasuk</b>
            <br />
          </h1>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="py-3 text-center">
        <div class="container">
          <div class="row">
            <div class="col-lg-4 col-md-6 p-4">
              <img src="../assets/svg/icon PHP Hosting_PHP Semua Versi.svg" width="80" height="80" />
              <h3>
                <b>PHP Semua Versi</b>
              </h3>
              <p>
                Pilih mulai dari PHP 5.3 s/d PHP 7
                <br />Ubah sesuka Anda!
              </p>
            </div>
            <div class="col-lg-4 col-md-6 p-4">
              <img src="../assets/svg/icon PHP Hosting_My SQL.svg" width="80" height="80" />
              <h3>
                <b>MySQL Versi 5.6</b>
              </h3>
              <p>
                Nikmati MySQL versi terbaru, tercepatdan
                <br />kaya akan fitur.
              </p>
            </div>
            <div class="col-lg-4 col-md-6 p-4">
              <img src="../assets/svg/icon PHP Hosting_CPanel.svg" width="80" height="80" />
              <h3>
                <b>Panel Hosting cPanel</b>
              </h3>
              <p>
                Kelola Website dengan panel canggih yang
                <br />familiar di hati Anda.
              </p>
            </div>
            <div class="col-lg-4 col-md-6 p-4">
              <img src="../assets/svg/icon PHP Hosting_garansi uptime.svg" width="80" height="80" />
              <h3>
                <b>Garansi Uptime 99.9%</b>
              </h3>
              <p>Data center yang mendukung kelansungan website Anda 24/7.</p>
            </div>
            <div class="col-lg-4 col-md-6 p-4">
              <img src="../assets/svg/icon PHP Hosting_InnoDB.svg" width="80" height="80" />
              <h3>
                <b>Database InnoDB Unlimited</b>
              </h3>
              <p
                contenteditable="true"
              >Jumlah dan ukuran database yang tumbuh sesuai kebutuhan Anda.</p>
            </div>
            <div class="col-lg-4 col-md-6 p-4">
              <img src="../assets/svg/icon PHP Hosting_My SQL remote.svg" width="80" height="80" />
              <h3>
                <b>Wildcard Remote MySQL</b>
              </h3>
              <p>
                Mendukung s/d 25 max_user_connections
                <br />dan 100 max_connections.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Packeges",
  props: {
    msg: String
  }
};
</script>
<style scoped>
@font-face {
  font-family: "montserrat";
  src: url("../assets/fonts/montserrat/Montserrat-Bold.otf");
  font-weight: bold;
  font-style: normal;
}
h3 {
  font-family: montserrat;
}
</style>

