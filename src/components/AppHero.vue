<script>
    export default {
        name: 'AppHero',
        data() {
            return {
                
            }
        }
    }
</script>

<template>
    <div class="hero">
        <img src="../assets/img/jumbotron.jpg" alt="">
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

.hero{
    height: 450px;

        img{
            height: 100%;
            width: 100%;
            object-fit: cover;
            object-position: top;
        }
}


</style>