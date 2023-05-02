<script>
    export default{
        name: "AppHero",
        data() {
            return {
                
            }
        }
    }

</script>

<template>

    <div class="jumbotron jumbotron-fluid">
        <div class="container text-white">
            <h1 class="display-4">Fluid jumbotron</h1>
            <p class="lead">This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
        </div>
    </div>

</template>

<style scoped>
    .jumbotron{
        background-image: url(../assets/03.webp);
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }
</style>