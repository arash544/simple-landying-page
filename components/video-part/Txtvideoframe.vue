<template>
<div class="xl:w-1/2 lg:flex sm:flex md:flex sm:w-full sm:justify-center sm:items-center sm:text-center md:w-full md:justify-center md:items-center md:text-center xl:flex wrapper flex-wrap flex-col xl:justify-baseline xl:items-start xl:pl-32 xl:pt-12 xl:pb-12 xl:pr-6 overflow-hidden">
    <h2 v-if="title" class="mt-8 text-3xl font-semibold">{{title}}</h2>
    <h2 v-else class="mt-12 text-3xl font-bold">

        {{head}}
    </h2>
    <h4 v-if="header" class="mt-8 text-2xl font-thin ">{{header}}</h4>
    <h4 v-else class="mt-2 text-left md:text-center  md:w-2/3  text-2xl xl:w-4/5 xl:text-left sm:text-center sm:w-2/3 lg:w-3/4 font-thin ">

        {{body}}
    </h4>
    <p class="mt-8 text-4xl font-semibold xl:w-1/2 xl:text-left">{{txt}}</p>
    <div class=" flex flex-row mt-12 ">
        <figure class=" flex flex-col w-full">
            <img class="w-full" :src="img" />
            <figcaption class="pt-2 text-base font-bold">{{footer}}</figcaption>
        </figure>
        <figure class=" flex flex-col w-full ml-2">
            <img class="w-full" :src="pic" />
            <figcaption class="pt-2 text-base font-bold">{{footer}}</figcaption>
        </figure>
    </div>

</div>
</template>

<script>
export default {
    name: "Txtvideoframe",
    props: ['title', 'header', 'txt', 'img', 'pic', 'footer', 'body', 'head']
}
</script>

<style lang="scss" scoped>
.wrapper {
    @media only screen and (max-width: 500px) {
        padding: 15px
    }

    @media only screen and (max-width: 768px) {
        padding: 15px
    }

}
</style>
