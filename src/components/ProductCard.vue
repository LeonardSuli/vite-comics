<script>
export default{
  name: 'ProductCard',
  props: {
    thumb: String,
    series: String,
    price: String
  }
}
</script>


<template>

    <div class="card">

        <img :src="thumb" alt="">
        <h4>{{ series }}</h4>
        <span>{{ price }}</span>

    </div>

</template>


<style scoped>

.card img{
  width: 100%;
  aspect-ratio: 2/3;
}

.card span{
  font-size: 12px;
}

.card:hover{
  transform: scale(1.1);
  box-shadow: 0 0 20px var(--dc-gray);

}
</style>