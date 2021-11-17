<template>
    <div id="menu">
        <ul>
            <li>
                <a href="/">Home</a>
            </li>
            <li>
                <a href="/page">Pagina</a>
            </li>
        </ul>
    </div>
</template>
<script>
export default {
    name: 'Menu'
}
</script>
<style scoped>
#menu {
    display: flex;
    
}
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: inline-block;
    margin: 0 10px;
}
</style>
