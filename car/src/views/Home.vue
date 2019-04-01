<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <div>
      <p>vuex-state-cont</p>
      <p>{{ count }}</p>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

import { mapState } from "vuex"

export default {
  name: 'home',
  components: {
    HelloWorld
  },
  data() {
    return {
      
    }
  },
  computed: {
  localComputed () { /* ... */ },
  ...mapState({
    count
  })
}
}
</script>
