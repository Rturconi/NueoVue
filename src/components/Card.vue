<script setup>
const props = defineProps ({
    img: String,
    title: String,
    descripcion: String,
    button: String
})
</script>

<template>
<div class="card" style="width: 18rem;">
  <img :src="img" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">{{title}}</h5>
    <p class="card-text">{{descripcion}}</p>
    <a href="#" class="btn btn-primary">{{ button }}</a>
  </div>
</div>
</template>