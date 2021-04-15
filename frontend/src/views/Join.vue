<template>
  <div>
    회원가입
    <div>
      <div>
        <label for="id">ID</label>
        <input 
          v-model="uid"
          type="text" 
          id="id"
        >
      </div>
      <div>
        <label for="password">비밀번호 확인</label>
        <input 
          v-model="password"
          type="password" 
          id="password"
        >
      </div>
      <div>
        <label for="passwordConfirm">비밀번호 확인</label>
        <input 
          v-model="passwordConfirm"
          type="passwordConfirm" 
          id="passwordConfirm"
        >
      </div>
    </div>
    <button>회원가입</button>
  </div>
</template>

<script>
export default {
  name:'Join',
  data(){
    return {
      uid:'',
      password:'',
      passwordConfirm:''
    }
  },
}
</script>

<style>

</style>