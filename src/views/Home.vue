<template>
  <div class="home">
    <HelloWorld msg="Esse é o msg do view/Home que passo para o componente filho"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
