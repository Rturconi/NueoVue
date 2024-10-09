<script setup>
import Card from './Card.vue'

import Akira from '../assets/akira.jpg'
import Hxh from '../assets/hxh.jpg'
import Eva from '../assets/eva.jpg'
import Hellsing from '../assets/hellsing.jpeg'

</script>

<template>

    <h2 style="color: rgb(59, 168, 142);">Mis animes favoritos.</h2>

    <!-- cards -->
    <div class="row d-flex justify-content-center" style="gap: 10px;">
        <Card :img="Akira" title="Akira" 
        descripcion="Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam quia fuga aut rem eligendi nemo commodi dolore
        optio expedita beatae, voluptatem iste eius id velit eum? Facere hic ut minus." 
        button="Kaneda!!!" />
        <Card :img="Hxh" title="Hunter x Hunter" 
        descripcion="Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam quia fuga aut rem eligendi nemo commodi dolore
        optio expedita beatae, voluptatem iste eius id velit eum? Facere hic ut minus." 
        button="Gooooooooooon!" />
        <Card :img="Eva" title="Neon Genesis Evangelion" 
        descripcion="Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam quia fuga aut rem eligendi nemo commodi dolore
        optio expedita beatae, voluptatem iste eius id velit eum? Facere hic ut minus." 
        button="Subíte al Eva!" />
        <Card :img="Hellsing" title="Hellsing" 
        descripcion="Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam quia fuga aut rem eligendi nemo commodi dolore
        optio expedita beatae, voluptatem iste eius id velit eum? Facere hic ut minus." 
        button="Draculón!" />
    </div>

    
</template>