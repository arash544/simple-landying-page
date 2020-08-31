<template>
<div class="flex flex-row flex-wrap justify-center items-stretch  mt-24 w-full ">
    <Cardframe class="max-w-sm xl:max-w-md lg:max-w-md md:max-w-xl sm:max-w-xl hover:shadow-lg transition duration-500 ease-in-out  hover: transform hover:-translate-y-10 hover:scale-80" img="/about.jpeg" title="The Coldest Sunset" text="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil." tags="#photography" tagss="#travel" tagsss="#winter" shows="true" shown="true" show="true" />
    <Cardframe class="max-w-sm xl:max-w-md lg:max-w-md md:max-w-xl sm:max-w-xl hover:shadow-lg transition duration-500 ease-in-out  hover: transform hover:-translate-y-10 hover:scale-80" img="/card3-a.jpg" title="The Coldest Sunset" text="Lorem ipsum dolor sit amet, consectetur  Maiores et perferendis eaque, exercitationem praesentium nihil." tags="#photography" tagsss="#winter" shows="true" />
    <Cardframe class="max-w-sm xl:max-w-md lg:max-w-md md:max-w-xl sm:max-w-xl hover:shadow-lg transition duration-500 ease-in-out  hover: transform hover:-translate-y-10 hover:scale-80" img="/lifestyle.jpeg" title="Living Good Moments" text="Lorem ipsum   Voluptatibus quia, nulla! Maioresdolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et." tags="#photography" tagss="#travel" tagsss="#winter" show="true" shows="true" />
    <Cardframe class="max-w-sm xl:max-w-md lg:max-w-md md:max-w-xl sm:max-w-xl hover:shadow-lg transition duration-500 ease-in-out  hover: transform hover:-translate-y-10 hover:scale-80" img="/about.jpeg" title="Travel Good Moments" text="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et." tags="#photography" tagss="#travel" tagsss="#winter" show="true" shown="true" />

</div>
</template>

<script>
import Cardframe from './Cardframe'
export default {
    name: "Cards",
    components: {
        Cardframe
    }
}
</script>

<style lang="scss" scoped>

</style>
