<script>
    export default {
        name: 'TopFooter',
        data() {
            return {
                
            }
        }
    }
</script>

<template>
    <footer>
        <div class="footer-top">
            <div class="container">
                <div class="footer-left">
                    <div class="col-33">
                        <h4>
                            DC COMICS
                        </h4>
                        <ul>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                        </ul>
                        <h4>
                            DC COMICS
                        </h4>
                        <ul>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                        </ul>
                    </div>
                    <div class="col-33">
                        <h4>
                            DC COMICS
                        </h4>
                        <ul>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                        </ul>
                        
                    </div>
                    <div class="col-33">
                        <h4>
                            DC COMICS
                        </h4>
                        <ul>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                            <li>
                                character
                            </li>
                           
                        </ul>
                        
                    </div>
                </div>
            </div>
        </div>
    </footer>
    
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

footer{
    .footer-top{
        
        
        background-image: url('../assets/img/footer-bg.jpg');
        color: white;

        .container{
            background-image: url('../assets/img/dc-logo-bg.png');
            background-repeat: no-repeat;
            background-position: 100%;

                .footer-left{
                    width: 30%;
                    display: flex;

                     .col-33{
                        width: 33%;
                        padding: 20px;

                            h4{
                                padding: 10px 0;
                            }

                            ul{
                                
                            }
                     }
                }
        }
    }
}

</style>