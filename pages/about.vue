<template>
  <div>
    <h2>About</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non nemo dolore nostrum! Delectus voluptate beatae vero at, necessitatibus ab id asperiores sed temporibus iure omnis facere distinctio quia sequi consequuntur.</p>
    <div>  {{ data }}</div>
  
  </div>
</template>

<script setup>
/*const {data}=await useFetch('/api/ninja?name=mario')*/
//const {data}=await useFetch('/api/ninja?name=mario',{method:'post',body:{age:30}})
const {data}=await useFetch('/api/currency/EUR')
</script>

<style  scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>