<template>
  <div class="m-user">
    <template v-if="user">
      欢迎你，<span class="username">{{ user }}</span>
      <nuxt-link to="/exit">退出</nuxt-link>
    </template>
    <template v-else>
      <nuxt-link to="/login" class="login">登陆</nuxt-link>
      <nuxt-link to="/register" class="register">注册</nuxt-link>
    </template>
  </div>
</template>

<script>
export default {
  name: 'User',
  data() {
    return {
      user: ''
    }
  }
}
</script>

<style lang="scss" scoped></style>
