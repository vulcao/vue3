<template>
    <div>
        <h4 v-bind:class="[cfcor]">{{ cftexto }} <button @click="$emit('executaEmit')">gogogo</button></h4>
    </div>
</template>
<script>
export default {
    name: 'ComponenteFilho',
    props: {
        cftexto: String,
        cfcor: String
    },
    emits: ['executaEmit']
}
</script>
<style scoped>
.red {
    color: red
}
.tan {
    color: tan;
}
.purple {
    color: purple
}
</style>