<template>
  <div class="about">
    <img alt="Vue logo" src="../assets/logo.png">
    <Demo msg="This is demo page!"/>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'
import Demo from '@/components/Demo.vue'

@Options({
  components: {
    Demo
  }
})
export default class Home extends Vue {
  // const state: any ={
  //   data: 0
  // }
}
</script>
