<script lang="ts" setup>
import Container from "./Container.vue"
</script>
<template>

    <footer>
        <Container>
            <div class="footerText">
                <img src="/images/Frame.svg" alt="">
                <span>Feliz Natal</span>
            </div>
            <div class="footerRedes">

                <ul>
                    <li>
                        <a href="">
                            <img src="/images/Vector.svg" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="/images/youtube.svg" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="/images/linkedin.svg" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="/images/instagram.svg" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="/images/facebook.svg" alt="">
                        </a>
                    </li>
                </ul>

            </div>
        </Container>
    </footer>

</template>

<style lang="scss">

    footer{
        padding: 20px;
        .container{
            display: flex;
            justify-content: space-between;
            align-items: center;
            .footerText{
                display: flex;
                justify-content: center;
                align-items: center;
                img{
                    margin-right: 12px;
                }
            }
            ul{
                flex-wrap: wrap;
                display: flex;
                li{
                    background-color: #f4d9dc;
                    height: 45px;
                    width: 45px;
                    border-radius: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    margin-right: 12px;
                    &:last-child{
                        margin-right: 0;
                    }
                }
            }
        }
    }

</style>