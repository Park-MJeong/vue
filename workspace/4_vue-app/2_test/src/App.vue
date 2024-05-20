<template lang="">
  <CheckboxItem></CheckboxItem>
  <h1>APP테스트</h1>
</template>
<script>
// 지역 컴포넌트 등록시에는 주석해제
import CheckboxItem from './components/CheckboxItem.vue';
export default {
  
  name: 'App',
  // 지역컴포넌트 등록시에는 주석 해제
  components : {CheckboxItem}
}
</script>
<style lang="">
  
</style>