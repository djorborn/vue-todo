<template lang="pug">
  #register.section
    .container
      register-form
</template>

<script>
import registerForm from './register.form';

export default {
  name: 'register',
  components: {
    'register-form': registerForm
  }
}
</script>

<style lang="css">
</style>
