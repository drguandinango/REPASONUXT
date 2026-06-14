<!-- <template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>
 --><script  lang="ts"  setup>
  const count=ref(10);
  await sleep(2000);
  count.value=20
 </script>

<!--  <template>
  <div>
   <h1>holamundo </h1>
  </div>
</template> -->

<template>
  <div>
    <h1>Hola Mundo - {{ count }}</h1>
    
    <button @click="count++">Click me</button>
  </div>
</template>