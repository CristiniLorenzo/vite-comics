<script>
    export default {
        name: 'AppMain',
        data() {
            return {
                
            }
        }
    }
</script>

<template>
    <main>
        <div class="container d-flex">
            <div class="top-main">
                content goes here
            </div>

        </div>
    </main>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

main{
    background-color: #1C1C1C;
    height: 100px;
    color: white;

    .container{
    height: 100%;
    align-items: center;
    }
}

</style>