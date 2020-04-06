<template>
  <div class="home">
    <p>Home</p>
    <button v-on:click="onclick">トップへ</button>
  </div>
</template>
<script>
  export default{
    methods: {
      onclick(){
        this.$router.push('about')
      }
    }
  }
</script>