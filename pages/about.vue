 <template>
  <div>
    <h1>About Dadjokes</h1>
    <p>This is an app that displays corny Dadjokes</p>


    <img src="../assets/Images/laughing-men.jpeg" class="laughing-men" /><br/><br/><br/>
    <img src="../assets/Images/laughing-women.jpeg" class="laughing-women" />
  </div>
</template>
 
 <script>
export default {
  head() {
    return {
      title: "About the app",
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
 
 <style>
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