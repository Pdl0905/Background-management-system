<template>
  <!-- 登录页 -->
  <div class="box">
    <div class="login">
      <b>登录</b>

      <div class="user">
        <input type="text"  placeholder="请输入用户名"/>
      </div>

      <div class="pass">
        <input type="password" placeholder="请输入密码"/>
      </div>

      <div class="btn">
          <input type="button" value="登录" /></div>
    </div>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {};
  },
  methods: {},
  mounted() {},
};
</script>
<style scoped>
.box {
  width: 100vw;
  height: 100vh;
  background: linear-gradient(left, #563443, #303d5f);
  position: relative;
}
.login {
  width: 600px;
  height: 400px;
  background-color: #fff;
  position: absolute;
  margin: 125px 50%;
  transform: translate(-50%);
  border-radius: 10px;
}
.login b {
  font-size: 35px;
  text-align: center;
  display: block;
  margin: 33px auto;
}
 input{
    width: 320px;
    height: 40px;
    border-radius: 5px;
    border: 1px solid #ccc;
    margin-top: 12px;
    margin-left: 138px;
    outline: none;
}
.btn input{
    width: 320px;
    height: 40px;
    border-radius: 5px;
    background-color: #409eff;
    color: #fff;
    outline: none;
}
</style>