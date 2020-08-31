<template>
<div class="w-full flex flex-row flex-wrap justify-center items-center">
    <div class="w-full main flex flex-row flex-wrap justify-center items-center bg-no-repeat bg-cover bg-fixed sm:bg-local md:bg-scroll lg:bg-local xl:bg-fixed photo" style="background-image: url(/computer.jpg)">
        <Cardframe class="xl:ml-8 text-white border-white-800 border-solid border-2 p-4 " photo="/smart-tv.svg" header="The Coldest Sunset" txt="Lorem ipsum dolor sit amet, consectetur  Maiores et perferendis eaque, exercitationem praesentium nihil." />
        <Cardframe class="xl:ml-8 text-white border-white-800 border-solid border-2 p-4 " photo="/write.svg" header="The Coldest Sunset" txt="Lorem ipsum dolor sit amet, consectetur  Maiores et perferendis eaque, exercitationem praesentium nihil." />
        <Cardframe class="xl:ml-8 text-white border-white-800 border-solid border-2 p-4 " photo="/digital.svg" header="The Coldest Sunset" txt="Lorem ipsum dolor sit amet, consectetur  Maiores et perferendis eaque, exercitationem praesentium nihil." />

    </div>

</div>
</template>

<script>
export default {
    name: "Photoframe",

}
</script>

<style lang="scss" scoped>
.photo {
    height: 80vh;

    @media only screen and (max-width: 500px) {
        height: auto;
    }

    @media only screen and (max-width: 768px) {
        height: auto;
    }

    @media only screen and (max-width: 1200px) {
        height: auto;
    }

    @media only screen and (max-width: 1400px) {
        height: auto;
    }
}

.box {
    // margin-left: 32px
}

.main {
    filter: grayscale(100%)
}
</style>
