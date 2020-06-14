<template>
  <div class="container">
    <div class="row">
      <div class="container">
        <div class="row">
          <div class="text-center mx-auto col-md-12">
            <h1 class="pt-5">
              <b>Paket Hosting Singapura yang Tepat</b>
              <br />
            </h1>
            <h2 class="pb-4">Diskon 40 % + Domain SSL untuk Anda</h2>
          </div>
        </div>
        <div class="row" v-if="homes">
          <div v-for="(home, index) in homes" class="col-md-3 Pricing" :key="home.id">
            <div class="card-body text-center border p-0" :class="{ 'border-best' : index === 2}">
              <div class="w-100 border-bottom" :class="{ 'col-best' : index === 2}">
                <h3>
                  <b>{{ home.cate }}</b>
                </h3>
              </div>
              <div class="w-100 Pricing-margin border-bottom" :class="{ 'col-best' : index === 2}">
                <span>
                  <strike>Rp {{home.pricebefore}}</strike>
                </span>
                <h4>
                  <b>{{home.priceafter}}</b> /bln
                </h4>
              </div>
              <div class="w-100 border-top border-bottom Pricing-margin py-1 " :class="{ 'col-best2' : index === 2}">
                <span>
                  <b class="col-best4">{{home.user}}</b> Pengguna Terdaftar
                </span>
              </div>
              <ul v-for="(fiture,id) in home.fiture" class="list-unstyled pt-1" :key="id">
                <li>{{fiture.name}}</li>
              </ul>
              <div class="mb-2">
                <a href="#">
                  <img src="../assets/svg/Group10.svg" alt />
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import axios from "axios";
export default {
  name: "Pricing",
  data() {
    return {
      homes: []
    };
  },
  mounted() {
    this.load();
  },
  methods: {
    load() {
      axios
        .get("https://restapihome.herokuapp.com/api/home")
        .then(res => {
          this.homes = res.data; //respon dari rest api dimasukan ke users
        })
        .catch(err => {
          console.log(err);
        });
    }
  }
};
</Script>
<style scoped>
.Pricing {
  padding-left: 0px;
  padding-right: 0px;
}
.Pricing-margin {
  margin-bottom: 0px !important;
}

.border-best {
  border: 3px solid #008fee !important;
}
.col-best {
  background-color: #008fee !important;
  color: #ffffff !important;
}

.col-best2 {
  background-color: #007fde !important;
  color: #ffffff !important;
}

.col-best3 {
  position: relative !important;
  box-shadow: 0 5px 37px 4px rgba(11, 26, 56, 0.08) !important;
  z-index: 100;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
}
.col-best4 {
  font-weight: bold !important;
}
</style>


