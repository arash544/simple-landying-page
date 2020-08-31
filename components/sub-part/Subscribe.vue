<template>
<div class="w-full h-auto flex flex-row flex-wrap justify-center items-center pt-20 bg-gray-100">
    <Txtvideoframe head="Subscribe for latest updates" body="Indie folks start out by making something they want to read, that tell stories they want told.." />
    <Subinput txt="Sign In" />

</div>
</template>

<script>
import Subinput from './Subinput.vue'
export default {
    name: "Subscribe",
    components: {
        Subinput,
    }

}
</script>

<style lang="scss" scoped>

</style>
