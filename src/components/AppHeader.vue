<script>
    export default {
        name: 'AppHeader',
        data() {
            return {
                links: [
                    {
                        text: 'CHARACTER',
                        active: false
                    },
                    {
                        text: 'COMICS',
                        active: false
                    },
                    {
                        text: 'MOVIES',
                        active: false
                    },
                    {
                        text: 'TV',
                        active: false
                    },
                    {
                        text: 'GAMES',
                        active: true
                    },
                    {
                        text: 'COLLECTIBLES',
                        active: false
                    },
                    {
                        text: 'VIDEOS',
                        active: false
                    },
                    {
                        text: 'FANS',
                        active: false
                    },
                    {
                        text: 'NEWS',
                        active: false
                    },
                    {
                        text: 'SHOP',
                        active: false
                    },
                ]
            }
        }
    }
</script>

<template>
    <div class="container d-flex">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="nav ">
            <ul class="d-flex">
                <li v-for="link in links" 
                :class="{'active': link.active}">
                    <a href="#">{{ link.text }}</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

.container{
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;
}

li {
    padding: 35px 10px;
    
    a{
        color: black;
    }

    &.active{
        // color: $brand-primary;
        border-bottom: 5px solid $brand-primary;
    }

    
}

</style>