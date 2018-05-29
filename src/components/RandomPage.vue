<template>
  <div>
    <h1>This is a h1 header</h1>
    <p>This is a paragraph</p>
    You can use varialbe {{var1}}
  </div>
</template>
<script>
export default {
  name: 'RandomPage',
  data () {
    return {
      var1: 'by using {{var_name}}'
    }  
  }
}
</script>
<style scoped>

</style>

