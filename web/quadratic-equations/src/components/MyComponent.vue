<template>
    <div class="root">
        <input v-model="InputText">
<btn>Ввод</btn>
    </div>
</template>
<script>

export default {
    name:'MyComponent',
    data() {
        return {
            InputText: `Введите значение`
        }
    },
}
</script>