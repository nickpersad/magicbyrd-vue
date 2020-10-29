<template>
  <CanvasEditor class="editor" v-model="code" language="javascript" theme="vs-dark" automaticLayout="true" />
</template>

<script>
import CanvasEditor from 'vue-monaco'

export default {
  components: {
    CanvasEditor
  },

  data() {
    return {
      code: `const hello = () => {
    return "world";
}`
    }
  }
}
</script>

<style>
.editor {
  width: 100%;
  min-width: 800px;
  /* height: 800px; */
  height: 100vh;
}
</style>