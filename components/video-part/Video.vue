<template>
<div class="container flex-wrap flex flex-row  mt-32 max-w-full lg:justify-center lg:items-center bg-gray-300">
    <Txtvideoframe title="VIDEOS" header="TOP OF THE WEEK PLAYLIST" txt="Calling time on irresponsible junk food advertising" img="/phone.png" pic="/girl.webp" footer="Fig.1 - Trulli, Puglia, Italy." />
    <Videomainframe img="woman.png" />
</div>
</template>

<script>
import Txtvideoframe from './Txtvideoframe'
import Videomainframe from './Videomainframe'
export default {
    name: "Video",
    components: {
        Txtvideoframe,
        Videomainframe
    }
}
</script>

<style lang="scss" scoped>
// * {
//     border: 1px solid blue;
// }
</style>
