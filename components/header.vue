<template>
  <container bg="white" py="8">
    <c-image width="175px" src="https://res.cloudinary.com/xtellar/image/upload/v1584242872/chakra-ui/chakra-ui-vue.png" alt="Hire App" />
    <c-stack my="4" color="gray.500" is-inline spacing="3">
      <c-box d="flex" align-items="center">
        <c-icon mr="3" name="building" />
        <c-text font-size="sm" flex-shrink="no-wrap">
          Beijing, China 🇨🇳
        </c-text>
      </c-box>
      <c-box d="flex" align-items="center">
        <c-icon mr="3" name="users" />
        <c-text font-size="sm" flex-shrink="no-wrap">
          3 people
        </c-text>
      </c-box>
    </c-stack>
    <c-text color="gray.500" max-w="500px" font-size="sm">
      Chakra UI is a small team of developers and designers building tools to help other developers build better user interfaces.
    </c-text>
  </container>
</template>

<script>
import { CImage, CBox, CStack, CText, CIcon } from '@chakra-ui/vue'
import Container from '@/components/container'

export default {
  name: 'Header',
  components: {
    Container,
    CImage,
    CStack,
    CText,
    CIcon,
    CBox
  }
}
</script>

<style lang="scss" scoped>

</style>
