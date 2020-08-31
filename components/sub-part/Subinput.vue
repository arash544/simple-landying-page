<template>
<div class=" sm:w-full md:w-full lg:w-1/2 xl:w-1/2 flex flex-row flex-wrap justify-center items-center pb-10">
    <input class="inp-form shadow appearance-none border rounded xl:w-1/2 sm:w-1/2 md:w-1/2 lg:w-1/2 py-4 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" placeholder="Username">
    <button class="button-form bg-blue-900 hover:bg-white text-white  hover:text-blue-900 hover:border-blue-900 hover:border hover:border-solid font-bold py-4 px-8 ml-1 rounded focus:outline-none focus:shadow-outline" type="button">
        {{txt}}
    </button>
</div>
</template>

<script>
export default {
    name: "Subinput",
    props: ['txt']

}
</script>

<style lang="scss" scoped>
.button-form {
    border: none;

    &:hover,
    &:active,
    &:focus {
        border: 1px solid darkblue;
        outline: 0;
    }

    @media only screen and (max-width: 400px) {
        margin-top: 18px;
        width: 280px;
    }
}

.inp-form {
    @media only screen and (max-width: 400px) {
        // margin-top: 18px;
        width: 280px;
    }
}
</style>
