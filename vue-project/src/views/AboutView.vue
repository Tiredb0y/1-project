<script setup>
import landscape from '@/components/landscape.vue';
import divi from '@/components/divi.vue';
import sf from '@/components/sf.vue';
</script>
<template>
  <landscape style="margin-top: 10px;"></landscape>
  <div class="divii"> 
  <divi></divi>
  <divi></divi>
  <divi></divi>
  <divi></divi>
  </div>\
  <sf></sf>
 
</template>

<style scoped>
.divii{
  display: flex;
  justify-content: space-around;
}

</style>
