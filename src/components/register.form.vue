<template lang="pug">
  form#register-form
    .title Register
    .subtitle todo
    .field
      label Username
      .control.has-icons-left
        input.input(type="text" placeholder="Username")
        span.icon.is-left
          i.fa user
      label Email
      .control.has-icons-left
        input.input(type="email" placeholder="you@email.com")
        span.icon.is-left
          i.fa envelope
      label Password
        .control.has-icons-left
          input.input(type="password" placeholder="password")
          span.icon.is-left
            i.fa lock
    .field.is-grouped
      .control
        a(href="/#/login").button.is-text Login
        p.help Already Have An Account
      .control
        button.button(type="submit").is-primary Submit
        p.help Submit Registration
</template>

<script>

</script>

<style lang="css">
#register-form {
  max-width: 480px;
  margin: auto;
}
</style>
