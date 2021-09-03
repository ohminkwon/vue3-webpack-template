<template>
  <h1>{{message}}</h1>
  <HelloWorld />
</template>

<script>
import HelloWrold from '~/components/HelloWorld'

export default {
  components: {
    HelloWorld
  },
  data() {
    return{
      message: 'Hello Vue!!!'
    }  
  }
}
</script>
