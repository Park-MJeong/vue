<template lang="">
  <input type='checkbox' :checked='user.checked'>{{user.number}}-{{user.name}}
</template>
<script>
export default {
  name :'CheckboxItem2',
  props :['user']/* 객체가 넘어옴 */
  
}
</script>
<style lang="">
  
</style>