<template>
    <div>
       <Joke  v-for="joke in jokes" :key="joke.id" :id="joke.id" :joke="joke.joke"/>
       
    </div>
</template>

<script>
import Joke from '../../components/joke'
import axios from "axios";
export default {
    components: {
        Joke
    },
    data () {
        return {
           jokes: [],
           //error: ''
        };
    },

    async created() {
        const config = {
            headers: {
                Accept: "application/json"
            }
        };

        try {
            const res= await axios.get("https://icanhazdadjoke.com/search", config);

             //console.log(res.data);

            this.jokes = res.data.results;
            this.error = err;

        } catch (err) {
            console.log(err);
        }
    },


    head() {
    return {
      title: "Dad Jokes",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for corny dad jokes",
        },
      ],
    };
  },
}
</script>

<style scoped>

</style>





 