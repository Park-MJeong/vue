<template lang="">
  <h1>유저 정보 조회</h1>
  <ul>
    <CheckboxItem v-for = 'user in users' :key ='user.number'
    :user='user' />
  </ul>

</template>
<script>
import CheckboxItem from './components/CheckboxItem2.vue';
export default {
  name : 'App2',
  components :{CheckboxItem},
  
  data(){
    return{
      users : [
        {number:1, name : '데이식스',checked :true},
        {number:2, name : '루시'},
        {number:3, name : '고은성'},
        {number:4, name : '홍광호',checked :true},
      ]
    }
  }

}
</script>
<style lang="">
  
</style>