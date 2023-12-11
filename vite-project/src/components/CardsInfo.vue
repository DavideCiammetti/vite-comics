<script>
export default{
    name: 'cardsInfo',
    props:{
        image: String,
        title: String,
    },
}
</script>

<template>
    <div class="card">
        <img :src="image" :alt="title">
       <h4>{{ title }}</h4>
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables.scss' as *;
.card{
    padding: 15px;
    width: calc((100% - 15px) / 6);
    height: 186px;
    margin-bottom: 50px;
        img{
            width: 100%;
            height: 100%;
        }
        h4{
            color: $col-white;
        }   
}
</style>