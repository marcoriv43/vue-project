<template>
<div class="sidebar">
    <h2>Barra lateral</h2>
    <ul>
        <li><RouterLink to="/contador">Contador</RouterLink></li>
        <li><RouterLink to="/lista-de-tareas">Lista de tareas</RouterLink></li>
    </ul>
    
</div>
</template>

<script setup>

</script>

<style>
.sidebar {
    width: 200px;
    background-color: crimson;
    padding: 20px;
}
</style>