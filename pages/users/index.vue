<template>
  <div>
    <h1>Usuários</h1>
    <p>Página: {{ route.query.page }}</p>
    <p>Página: {{ $route.query.page }}</p>
  </div>
</template>

<script setup lang="ts">
const route = useRoute();
</script>
