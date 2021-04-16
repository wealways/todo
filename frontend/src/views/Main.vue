<template>
  <div>
    <div>
      로그인
    </div>
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
        <label for="password">password</label>
        <input 
          v-model="password"
          type="password" 
          id="password"
        >
      </div>
    </div>
    <button>로그인</button>
    <router-link to="/join">회원가입</router-link>
  </div>
</template>

<script>
export default {
  name:'Main',
  data(){
    return {
      uid:'',
      password:'',
    }
  },
}
</script>

<style>

</style>