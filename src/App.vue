<template lang="pug">
  #app
    v-toolbar
      v-toolbar-title Portfolio
      v-toolbar-items
        v-toolbar-side-icon
        v-toolbar-side-icon
        v-toolbar-side-icon
    router-view
    .background-image
      img(src="https://images.pexels.com/photos/67636/rose-blue-flower-rose-blooms-67636.jpeg?cs=srgb&dl=beauty-bloom-blue-67636.jpg&fm=jpg")
</template>

<style lang="sass">
#app
  font-family: "Avenir", Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  color: #2c3e50

.background-image
  display: flex
  position: fixed
  left: 0
  top: 25%
  img
    width: 50%
    height: 50%
</style>
