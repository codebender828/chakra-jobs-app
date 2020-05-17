<template>
  <c-theme-provider>
    <c-reset />
    <c-box border-top="5px solid" border-color="vue.400">
      <page-header />
      <nuxt />
    </c-box>
  </c-theme-provider>
</template>

<script>
import { injectGlobal } from 'emotion'
import { CThemeProvider, CBox, CReset } from '@chakra-ui/vue'
import PageHeader from '@/components/header'

export default {
  name: 'DefaultLayout',
  components: {
    CThemeProvider,
    CReset,
    CBox,
    PageHeader
  },
  created () {
    injectGlobal({
      'html, body': {
        backgroundColor: this.$chakra.theme.colors.gray[50]
      }
    })
  }
}
</script>
