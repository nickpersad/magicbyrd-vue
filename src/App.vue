<template>
  <CanvasEditor class="editor" v-model="code" language="javascript" />
</template>
<script>
// import HelloWorld from './components/HelloWorld.vue'
import CanvasEditor from './components/CanvasEditor.vue'

export default {
  name: 'App',
  components: {
    CanvasEditor
  }
}
</script>

<style>
html, body, #app {
	position: absolute;
	left: 0;
	top: 0;
	width: 100%;
	height: 100%;
	margin: 0;
	padding: 0;
	overflow: hidden;
}
</style>
