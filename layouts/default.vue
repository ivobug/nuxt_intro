<template>
  <div>
    <navbar></navbar>
    <nav>
      ...
    </nav>
    <nuxt />
  </div>
</template>

<script>
import navbar from '../components/navbar'
export default {
  components:{
    navbar
  }
}
</script>

<style scoped>
nav{
  color: aliceblue;
}

</style>
