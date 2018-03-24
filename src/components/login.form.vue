<template lang="pug">
  form#login-form
    .title Login
    .subtitle todo
    .field
      label.label Username
      .control.has-icons-left
        input.input(type="text"
                    placeholder="Username")
        span.icon.is-left
          i.fa user
      label.label Password
      .control.has-icons-left
        input.input(type="password"
                    placeholder="Password")
        span.icon.is-left
          i.fa lock
    .field
      .control
        label(for="checkbox")
          input(type="checkbox" name="checkbox")
          span Remember Me
    .field.is-grouped
      .control
        a(href='/#/register').button.is-text Register
      .control
        button.button(type="submit").is-primary Login
</template>

<script>
export default {
  name: 'login-form'
}
</script>

<style lang="css">
#login-form {
  max-width: 400px;
  margin: auto;
}
</style>
