<template>
  <div class="about">
    <h1>The number is:{{number}}</h1>
    <button @click="incrementar()" />
  </div>
</template>
<script>
  export default{
    name:"About",
    data(){
      return {
        number:0,
      }
    },
    methods:{
      incrementar(){
        this.number++;
      }
    }
  }
</script>
