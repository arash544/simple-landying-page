<template>
<div class="flex flex-row flex-wrap justify-center items-center w-full ">
    <Photoframe />

</div>
</template>

<script>
import Photoframe from './Photoframe'
// import Cardframe from './card-part/Cardframe'
// import Cards from './card-part/Cards'
export default {
    name: "Photo",
    components: {
        Photoframe,
        // Cardframe,
        // Cards
    }
}
</script>

<style lang="scss" scoped>

</style>
