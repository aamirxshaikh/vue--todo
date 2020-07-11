<template>
    <div>
        <p>Todo Item</p>
    </div>
</template>

<script>
export default {
    name: "TodoItem"
}
</script>

<style scoped>
    .todo-item {
        background: #F4F4F4;
        padding: 10px;
        border-bottom: 1px #CCC dotted;
    }

    .is-complete {
        text-decoration: line-through;
    }

    .del {
        background: #FF0000;
        color: #FFF;
        border: none;
        padding: 5px 9px;
        cursor: pointer;
        float: right;
    }
</style>