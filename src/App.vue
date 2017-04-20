<template>
  <div id="app">
    <keep-alive>
      <foo></foo>
    </keep-alive>
  </div>
</template>

<script>
import Foo from './Foo.vue'

export default {
  name: 'app',
  components: {
    Foo
  }
}
</script>
