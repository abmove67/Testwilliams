<template>
  <div class="home">

    <div class="header">
      <p>Header</p>
      <!-- <img class="logo-ws" src="../assets/williamssonoma.png" /> -->
    </div>

    <div class="body">
      <p>Body</p>
    </div>

    <div class="footer">
      <p>Footer</p>
    </div>

  </div>
</template>

<script>
export default {
  name: '',
  props: {
    msg: String
  }
}
</script>

<!-- Added "scoped" attribute to limit CSS to this component only -->
<style scoped>
.logo-ws{
  width: 150px;
  height: 120px;
}
.body{
    height: 1000px;
    width: 100%;
    border: 2px solid red;
}
.header{
  height: 100px;
  width: 100%;
  border: 2px solid blue;
}
.footer{
  height: 50px;
  width: 100%;
  border: 2px solid blue;
}

</style>
