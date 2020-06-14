<template>
  <div class="py-3 Call">
    <div class="container">
      <div class="row">
        <div class="col-md-7 p-4">
          <h4 class="text-white">
            Perlu
            <b class="Call2">Bantuan?</b> Hubungi Kami :
            <b class="Call2">0274-5305505</b>
          </h4>
        </div>
        <div class="col-md-5 text-center p-4">
          <img src="../assets/images/Group 12 (1).png" />
          <img />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Callcenter",
  props: {
    msg: String
  }
};
</script>
<style scoped>
.Call {
  background-color: #00a2f3;
}
.Call2 {
  font-weight: bold;
}
</style>
