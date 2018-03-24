<template lang="pug">
  #home
    .home-wrapper
      .section
        .container
          .panel
            input.input.panel-heading(placeholder="New List Title")
            .panel-block
              .field.has-addons
                .control.has-icons-left
                  input.input(placeholder="New Item")
                  span.icon.is-left
                    i.fa edit
                .control
                  button.button
                    span.icon
                      i.fa plus
</template>

<script>
export default {
}
</script>

<style lang="css">
.home-wrapper {
  max-width: 430px;
  margin: auto;
}
</style>
