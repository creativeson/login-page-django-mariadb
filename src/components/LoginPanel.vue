<!-- <style src="./LoginPanel/styles.css"></style> -->
<!-- <template src="./Login.html"></template> -->

<template src="./Login.html"></template>

<script>
export default {
  // 在这里可以编写组件的逻辑代码
  data() {
    return {
      username: '',
      password: ''
    };
  },
  methods: {
    login() {
      // 在这里处理登录逻辑
      if (this.username === 'user' && this.password === 'password') {
        alert('登录成功');
        // 登录成功后的操作，例如跳转到其他页面
      } else {
        alert('用户名或密码错误');
      }
    }
  }
};
</script>

<style scoped>
@import './styles.css';
</style>
