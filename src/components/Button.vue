<template>

    <button class="myButton">
        <img src="/images/gift.svg" alt="">
        <slot></slot>
    </button>

</template>

<style lang="scss" scoped>

    .myButton{
        background-color: #DA2535;
        border: none;
        color: #FFF;
        border-radius: 8px;
        padding: 10px;
        font-size: 16px;
        font-weight: 600;
        &:hover{
            cursor: pointer;
        }
        display: flex;
        align-items: center;

        justify-content: space-between;
        img{
            width: 20px;
            height: 20px;
            margin-right: 12px;
        }
    }

</style>