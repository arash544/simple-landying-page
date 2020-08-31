<template>
<div class="cards container w-auto m-8 lg:m-2 flex flex-row justify-center items-strech h-86 ">
    <div class=" max-w-sm xl:max-w-sm lg:max-w-md md:max-w-xl sm:max-w-xl rounded overflow-hidden ">

        <img v-if="img" class="w-full" :src="img" alt="caffee">

        <img v-else class="w-1/6  sm:w-1/5 md:w-1/4 md:ml-6 sm:ml-6 xl:ml-0 alte" :src="photo" alt="">

        <div class="px-2 py-5">
            <div v-if="title" class="font-bold text-xl mb-2 ">{{title}}</div>
            <div v-else class="font-extrabold text-2xl text-center md:text-left sm:text-left alter">{{header}}</div>
            <p v-if="text" class="text-gray-700 text-base">{{text}}</p>
            <p v-else class="text-white-700 text-base font-bold">{{txt}}</p>
        </div>
        <div class="px-6 pt-4 pb-2">
            <span v-if="shows" class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">{{tags}}</span>
            <span v-if="show" class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">{{tagss}}</span>
            <span v-if="shown" class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">{{tagsss}}</span>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: "Cardframe",
    props: ['borders', 'img', 'title', 'txt', 'text', 'tags', 'tagss', 'tagsss', 'show', 'shows', 'shown', 'photo', 'header'],
    // props: {
    //     boxShadow: {
    //         type: String,
    //     },

    // },
    // computed: {
    //     shape() {
    //         return {
    //             boxShadow: `${this.boxShadow}`
    //         }
    //     }
    // }

}
</script>

<style lang="scss" scoped>
.cards {
    width: 320px;
    flex-wrap: nowrap;

    @media only screen and (max-width: 1400px) {
        width: 1000px;
    }
}

.alte {
    @media only screen and (max-width: 600px) {
        margin-left: 18px;
        width: 80px;
    }

    // @media only screen and (min-width: 1300px) {
    //     margin-left: 0px;
    // }
}

.alter {
    @media only screen and (max-width: 600px) {
        text-align: left;
    }
}
</style>
