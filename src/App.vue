<!-- src/App.vue -->
<template>
  <div id="app">
    <ColorSelector />
  </div>
</template>

<script>
import ColorSelector from './pages/ColorSelector.vue';

export default {
  components: {
    ColorSelector,
  },
};
</script>