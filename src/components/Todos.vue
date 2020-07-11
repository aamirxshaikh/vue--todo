<template>
    <div>
        <div v-for="todo in todos" v-bind:key="todo.id">
            <h3>{{ todo.id }}</h3>
        </div>
    </div> 
</template>

<script>
export default {
    name: "Todos",
    props: ["todos"]
} 
</script>

<style lang="">
    
</style>