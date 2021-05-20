<template>
    <div>
        <div v-bind:key="todo.id" v-for="todo in todosList">
        <div>{{todo.title}}</div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'Todos',
    props: ['todoslist']
}
</script>
 
<style></style> 