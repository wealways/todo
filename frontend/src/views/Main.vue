<template>
  <q-page-container class="container">
    <q-page class="page">
      <div class="title">
        <h2>Todo</h2>
      </div>
      <div class="login">
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
    </q-page>
  </q-page-container>
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

<style scoped>
.container{

}
.page{
  padding:5rem;
}
</style>