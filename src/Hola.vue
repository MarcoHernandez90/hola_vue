<!-- eslint-disable vue/multi-word-component-names -->
<template>
    <div>
        <p>lorem ipsum</p>
        <div class="hola">{{ text }}</div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            text: 'Hola Vue'
        };
    }
}
</script>

<style>
.hola {
    color: mediumseagreen;
    font-size: large;
}
</style>