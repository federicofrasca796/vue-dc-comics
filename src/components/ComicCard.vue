<template>
    <div class="card col">
        <div class="card_thumb">
            <img :src="img" alt="">
        </div>
        <div class="card_info">
            {{comicsName}}
        </div>
    </div>

</template>

<script>
export default {
    props: {
        img: String,
        comicsName: String,
    },
}

</script>

<style scoped lang="scss">
    .card{
        &.col{
            width: calc(100% / 6);
            margin-bottom: 3rem;
        }
        .card_thumb{
            text-align: center;
        }
        img{
            height: 160px;
            width: 160px;
            object-fit: cover;
            object-position: top;
            margin-bottom: 1rem;
        }
        .card_info{
            text-transform: uppercase;
        }
    }

</style>