<template>
<div class="xl:w-1/2 lg:w-full md:w-full sm:w-full xl:flex lg:flex sm:flex md:flex xl:justify-start xl:items-start md:justify-center sm:justify-center lg:justify-center sm:items-center md:items-center lg:items-center pr-4 pl-4 pt-32 pb-24 overflow-hidden ">
    <img class="xl:w-2/3 lg:w-1/2 md:1/2 sm:1/2 h-auto object-center " :src="img" />
</div>
</template>

<script>
export default {
    name: "Videomainframe",
    props: ['img']
}
</script>

<style lang="scss" scoped>
// * {
//     border: 1px solid black
// }

// .wrap {
//     @media only screen and (max-width: 1100px) {
//         width: 100%;

//     }

//     img {
//         @media only screen and (max-width: 1100px) {
//             width: 90%;

//         }
//     }
// }
</style>
