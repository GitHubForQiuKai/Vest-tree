<template>
    <div></div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import treeNode from './tree-node.vue'

@Component({
  components: {
  treeNode
  },
  })
export default class App extends Vue {}
</script>
