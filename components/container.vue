<template>
  <c-box v-bind="$props" :px="[5, 10, 10, '10rem']">
    <slot />
  </c-box>
</template>

<script>
import { CBox } from '@chakra-ui/vue'

export default {
  name: 'Container',
  components: {
    CBox
  },
  extends: CBox
}
</script>
