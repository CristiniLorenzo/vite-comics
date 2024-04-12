<script>
    export default {
        name: 'BottomMain',
        data() {
            return {
                products: [
                    {
                        img: 'buy-comics-digital-comics.png',
                        text: 'DIGITAL COMICS',
                    },
                    {
                        img: 'buy-comics-merchandise.png',
                        text: 'DC MERCHANDISE',
                    },
                    {
                        img: 'buy-comics-subscriptions.png',
                        text: 'SUBSCRIPTION',
                    },
                    {
                        img: 'buy-comics-shop-locator.png',
                        text: 'COMIC SHOP LOCATOR',
                    },
                    {
                        img: 'buy-dc-power-visa.svg',
                        text: 'DC POWER VISA',
                        
                    }
                ],
                imagePath: '/src/assets/img/'
            }
        }
    }
</script>

<template>
    <main>
        <div class="container d-flex">
            <div class="products d-flex">
                <ul class="d-flex">
                    <li v-for="product in products" class="d-flex">
                        <img :src="imagePath + product.img" alt="">
                        <div>{{ product.text }}</div>
                    </li>
                </ul>
            </div>
        </div>
    </main>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

main{
    background-color: $brand-primary;
    height: 150px;
    color: white;

    .container{
    height: 100%;
    align-items: center;
    justify-content: center;
    
        li{
        padding: 20px;
        align-items: center;
            div{
                padding: 15px;
            }
            img{
            height: 50px;
        }
        }
        
    }
}

</style>

