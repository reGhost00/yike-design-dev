<template>
  <div class="yk-tree">Tree</div>
</template>
<script setup lang="ts">
import { TreeProps } from './tree'
import { createCssScope } from '../../utils/bem'

const bem = createCssScope('tree')

defineOptions({
  name: 'YkTree',
})
const props = withDefaults(defineProps<TreeProps>(), {
  id: '',
})
</script>
