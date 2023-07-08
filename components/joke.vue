<template>
    <div class="joke">
        <p> {{joke}} </p>
    </div>
</template>

<script>
export default {
    name: "Joke",
    props: ["joke", "id"]
}
</script>

<style scoped>
.joke {
    padding: 1rem;
    border-bottom: 1.5px solid #526488;
    margin: 1rem 0;
}
</style>