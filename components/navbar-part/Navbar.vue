<template>
<div class="w-full pt-6 ">
    <nav class="flex flex-row justify-center items-center w-full ">
        <ul class="flex flex-row justify-center items-center w-full ">
            <li><img src="/log.png" class="mr-10 w-22 h-12 bg-transparent img-nav" /></li>

        </ul>
        <ul class="flex flex-row justify-end items-center w-full ">
            <li><a class="mr-5 cursor-pointer">Home</a></li>
            <li><a class="mr-5 cursor-pointer">About</a></li>
            <li><a class="mr-5 cursor-pointer">Contact</a></li>
            <li class="button"><a class="mr-40 cursor-pointer"><button class="transition duration-500 ease-in-out  transform hover:translate-x-0-translate-x-full skew-x-0 hover:bg-color-black  bg-transparent hover:bg-blue-900 text-black-400 font-semibold  py-2 px-12 border border-black-500 hover:border-white hover:text-white rounded ">
                        Register
                    </button></a>
            </li>
        </ul>
    </nav>
</div>
</template>

<script>
export default {
    name: "Navbar"
};
</script>

<style lang="scss" scoped>
.button {
    @media only screen and (max-width: 768px) {
        display: none
    }
}

.img-nav {
    @media only screen and (max-width: 768px) {
        width: 80px;
        height: 30px;
        margin-left: 10px;
        margin-bottom: 5px
    }
}
</style>
