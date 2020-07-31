<template>
  <button @click="handleClick">
    <slot></slot>
  </button>
</template>
<script>
export default {
  name:'x-button',
  props:{
    type: String
  },
  methods:{
    handleClick(){
      console.log('hello world!')
    }
  }
}
</script>
<style scoped>
.x-button{
  display: inline-block;
  padding: 3px 6px;
  background-color: #000;
  color: #FFF;
}
</style>