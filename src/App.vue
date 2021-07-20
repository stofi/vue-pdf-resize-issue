<template>
  <div id="app">
    <h1>Welcome to Your Vue.js App</h1>
    <pdf
      src="https://raw.githubusercontent.com/mozilla/pdf.js/ba2edeae/web/compressed.tracemonkey-pldi-09.pdf"
    ></pdf>
  </div>
</template>

<script>
import Pdf from 'vue-pdf'

export default {
  components: {
    Pdf,
  },
}
</script>
