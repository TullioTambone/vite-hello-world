<script>
    export default{
        name: "MyTitle",
        data() {
            return {
                name: 'helloWorld',
            }
        }
    }

</script>

<template>
    <div>
        <h1>{{ name }}</h1>
    </div>
</template>

<style scoped>

    h1{
        color: red;
    }

</style>