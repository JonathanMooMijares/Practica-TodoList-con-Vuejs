<script lang="ts" setup>
defineProps<{
    fueCompletado?: boolean | false
}>();

</script>

<template>
    <label :class="{ 'completado': fueCompletado }">
        <input type="checkbox" :checked="fueCompletado"/>
        <slot></slot>
    </label>
</template>

<style scoped>
label {
    cursor: pointer;
}

.completado {
    text-decoration: line-through;
}
</style>