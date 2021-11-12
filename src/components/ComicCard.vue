<template>
    <div class="card col">
        <img :src="img" alt="">
        <h3 class="card_info">
            {{comicsName}}
        </h3>
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
        }
        img{
            height: 150px;
            width: 150px;
            object-fit: cover;
            object-position: top;
            margin-bottom: 1rem;
        }
        .card_info{
            text-transform: uppercase;
        }
    }

</style>