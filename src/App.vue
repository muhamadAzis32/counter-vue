<script setup>

import { ref } from 'vue';
const count = ref(0)

</script>

<template>
  <div>
    <h1>Counter</h1>
    <span class="" id="value">{{ count }}</span>
    <div>
      <button @click="count--" id="decrease">-</button>
      <button @click="count++" id="increase">+</button>
    </div>
  </div>
</template>

// hanya digunkan pada komponen ini saja
<style scoped>
h1{
  font-size: 50px;
  color: red;
}

button{
  height: 30px;
  width: 50px;
  margin-right: 5px;
  margin-top: 10px;
}

</style>