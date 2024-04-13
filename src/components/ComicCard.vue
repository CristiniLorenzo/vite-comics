<script>
export default {
    name: 'ComicCard',
    props: {
        comicInfo: Object 
    }
    // props: ['image','title']
}
</script>

<template>
    <div class="card">
        <div>
            <img :src="comicInfo.thumb" alt="">
        </div>

        <h3>{{comicInfo.series}}</h3>
    </div>
</template>

<style>
@use '../style/partials/variables' as *;

.card{
    width: calc((100% / 6) - 20px);
    margin: 10px 0;
        h3{
            margin: 10px 0;
        }

        img{
            width: 100%;
            height: 200px;
            display: block;
            object-fit: cover;
            object-position: top;
        }

}

</style>