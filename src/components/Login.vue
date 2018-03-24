<template lang="pug">
  #login.section
    .container
      login-form

</template>

<script>
import loginForm from './login.form'

export default {
  name: 'login',
  components: {
    'login-form': loginForm,
  },
}

</script>

<style lang="css">
</style>
