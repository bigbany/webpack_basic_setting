<template>
  <h1>{{ count }}</h1>
</template>

<script>
export default{
  data(){
    return{
      count: 2
    }
  },
  beforeCreate(){
    console.log('before created!',this.count)

  },
  created(){
    console.log('created!',this.count)
  },
   beforeMount(){
    console.log(' before mounted!')
    console.log(
      document.querySelector('h1')
    )
    
  },
  mounted(){
    console.log('mounted!')
    console.log(
      document.querySelector('h1')
    )
  }
}
</script>


<style >

</style>