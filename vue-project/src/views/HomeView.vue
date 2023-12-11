<script setup>
import images from '../components/images.vue';
import landscape from '../components/landscape.vue'
</script>

<template>
  <main>
    <div class="image-container">
    <images class="imgss"></images>
    <images class="imgss"></images>
    </div>
Lorem ipsum dolor sit amet consectetur adipisicing elit. Et, tempore. 
Dolor maiores tempora dicta, magni ex, sunt 
temporibus possimus vitae, dolores illum non architecto iure. Deleniti
 doloremque magni doloribus totam.
 <br>
 <landscape></landscape>
 <br><div class="divtdiv">
 <img src="../assets/MicrosoftTeams-image551ad57e01403f080a9df51975ac40b6efba82553c323a742b42b1c71c1e45f1.jpg" class="imgg">
 Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore perferendis accusamus voluptate voluptatibus nostrum harum illo animi eos. Eaque necessitatibus aspernatur fugit soluta repellat iste dicta repellendus magni quae possimus!
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere eius optio, asperiores sit unde error aliquid quas est. Magni facere exercitationem commodi repellat fuga eveniet tempore veritatis quis illum atque?
Lorem ipsum dolor sit amet consectetur adipisicing elit. In, doloribus perferendis sapiente repellendus molestias voluptates non odit? Ea consequatur impedit, illum natus dolores voluptatem, eius voluptatum culpa aut assumenda itaque. 
</div>
</main>
</template>
<style scoped>
.divtdiv{
  display: flex;
  margin-bottom: 10px;
}
.imgg{
  width: 200px;
  height: 200px;
}
.image-container{
    display: flex;            
        }
        .imgss{
         width: 50%; 
         height: auto;

        }
MAIN{
  display: flexbox;
  flex-wrap: wrap;
}

</style>