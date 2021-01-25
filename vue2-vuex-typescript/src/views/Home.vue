<template>
  <div>
    <TInput></TInput>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import TInput from 'vue-tailwind/dist/t-input'

@Component({
  components: {
    TInput
  }
})
export default class Home extends Vue {}
</script>
