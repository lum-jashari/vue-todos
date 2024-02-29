<script setup>
const props = defineProps({
    todo: {
        type: Object,
        required: true,
    },
});
</script>

<template>
    <li>
        <input type="checkbox" :checked="todo.isCompleted" />
        <div class="todo">
            <input type="text" />
            <span>{{ todo.todo }}</span>
        </div>
    </li>
</template>

<style lang="scss" scoped></style>
