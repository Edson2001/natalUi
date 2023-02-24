<template>

    <button class="myButton">
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
    }

</style>