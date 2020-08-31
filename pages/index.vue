<template>
<section>
    <Cards />
    <Video />
    <Photo />
    <Subscribe />
</section>
</template>

<script>
import Cards from '@/components/card-part/Cards'
import Video from '@/components/video-part/Video'
import Photo from '@/components/fix-photo/Photo'
import Subscribe from '@/components/sub-part/Subscribe'
export default {
    components: {
        Cards,
        Video,
        Photo,
        Subscribe
    }
}
</script>

<style>

</style>
