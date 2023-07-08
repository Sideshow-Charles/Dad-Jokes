<template>
  <div>
      <div class="sub-head">
      <h1>Welcome to the best corny dad jokes on the web!</h1>
      <p><strong>Some Lorem crap!</strong></p>
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nemo facilis
        porro magnam, recusandae fuga illum iure ea laboriosam, officiis
        voluptas
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nemo facilis
        porro magnam, recusandae fuga illum iure ea laboriosam, officiis
        voluptas
      </p></div>
      <br />

    <img src="../assets/Images/laughing-men.jpeg" class="laughing-men" /><br/><br/><br/>
    <img src="../assets/Images/laughing-women.jpeg" class="laughing-women" />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Welcome to dad jokes",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for corny dad jokes",
        },
      ],
    };
  },
};
</script>

<style scoped>
.sub-head {
  /*font-size: 30px;*/
  padding: 0 10px 0 10px;
  line-height: 2;
}

.laughing-men {
  position: relative;
  width: 25%;
  /*top: 50% !important;*/
  left: 70%;
}

.laughing-women {
  position: relative;
  width: 25%;
  /*top: 10% !important;*/
  left: 1%;
}

</style>
