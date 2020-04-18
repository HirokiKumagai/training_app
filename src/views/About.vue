<template>
  <div class="about">
    <p>about</p>
    <button v-on:click="onclick">トップへ</button>
  </div>
</template>
<script>
  export default{
    methods: {
      onclick(){
        this.$router.push('/')
      }
    }
  }
</script>