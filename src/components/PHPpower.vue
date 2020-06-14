<template>
  <div class="container">
    <div class="row">
      <div class="text-center mx-auto col-md-12">
        <h1 class="pt-3 pb-4">
          <b>Powerful dengan Limit PHP Lebih Besar</b>
          <br />
        </h1>
      </div>
    </div>
    <div class="row">
      <div class="col-md-12 Power-margin">
        <div class="row">
          <div class="col-md-6 border Power">
            <ul class="list-unstyled text-justify Power-margin2">
              <div class="w-100 border-bottom">
                <li class="p-1">
                  <b>
                    <img
                      width="17"
                      height="17"
                      alt
                      src="../assets/svg/tick.svg"
                      class="d-inline-block"
                    />
                    <span class="pl-5">execution time 300s</span>
                  </b>
                </li>
              </div>
              <div class="w-100 border-bottom">
                <li class="p-1">
                  <b>
                    <img
                      width="17"
                      height="17"
                      alt
                      src="../assets/svg/tick.svg"
                      class="d-inline-block"
                    />
                    <span class="pl-5">max execution time 300s</span>
                  </b>
                </li>
              </div>
              <div class="w-100 border-bottom">
                <li class="p-1">
                  <img
                    width="17"
                    height="17"
                    alt
                    src="../assets/svg/tick.svg"
                    class="d-inline-block"
                  />
                  <span class="pl-5">
                    <b>php memory limit 1040 MB</b>
                  </span>
                </li>
              </div>
            </ul>
          </div>
          <div class="col-md-6 border Power">
            <ul class="list-unstyled text-justify Power-margin2">
              <div class="w-100 border-bottom">
                <li class="p-1">
                  <img
                    width="17"
                    height="17"
                    alt
                    src="../assets/svg/tick.svg"
                    class="d-inline-block"
                  />
                  <b>
                    <span class="pl-5">post max size 128 MB</span>
                  </b>
                </li>
              </div>
              <div class="w-100 border-bottom">
                <li class="p-1">
                  <img
                    width="17"
                    height="17"
                    alt
                    src="../assets/svg/tick.svg"
                    class="d-inline-block"
                  />
                  <b>
                    <span class="pl-5">upload maxfiles size 128MB</span>
                  </b>
                </li>
              </div>
              <div class="w-100 border-bottom">
                <li class="p-1">
                  <img
                    width="17"
                    height="17"
                    alt
                    src="../assets/svg/tick.svg"
                    class="d-inline-block"
                  />
                  <b>
                    <span class="pl-5">max input vars 2500</span>
                  </b>
                </li>
              </div>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PHPpower",
  props: {
    msg: String
  }
};
</script>
<style scoped>
.Power {
  padding-left: 0px;
  padding-right: 0px;
}
.Power-margin {
  padding-left: 108px !important;
  padding-right: 123px !important;
  margin-bottom: 0px !important;
}
.Power-margin2 {
  margin-bottom: 0px !important;
}
</style>

