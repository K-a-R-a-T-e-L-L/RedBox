<template>
  <div :style="RedBox"></div>
  <img src=""/>
</template>

<script>
export default {
  name: 'MainComponent',
  computed: {
    RedBox(){
      return{
        width: '40px',
        height: '40px',
        backgroundColor: 'red'
      }
    }
  }
}
</script>


<style scoped>

</style>
