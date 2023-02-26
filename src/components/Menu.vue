<script lang="ts"></script>
<template>

    <nav>

        <h1>
            <img src="/images/Frame.svg" alt="">
            <a href="">Feliz Natal</a>
        </h1>
        <ul>
            <li>
                <a href="">Início</a>
            </li>
            <li>
                <a href="">Acessórios</a>
            </li>
            <li>
                <a href="">Doação</a>
            </li>
            <li>
                <a href="">Contacto</a>
            </li>
        </ul>

    </nav>

</template>
<style lang="scss" scoped>

nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    ul{
        display: flex;
        align-items: center;
        li{
            margin-right: 22px;
            font-weight: 500;
        }
    }
    a{
        color: #161212;
    }
    h1{
        font-weight: 500;
        font-size: 24px;
        line-height: 36px;
        display: flex;
        align-items: center;
        img{
            margin-right: 12px;
        }
    }
    padding: 10px;

}

</style>