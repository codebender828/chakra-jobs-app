<template>
  <c-link
    v-bind="$props"
    rounded="lg"
    d="block"
    bg="white"
    shadow="sm"
    text-decor="none"
    :_hover="{ textDecor: 'none' }"
    px="6"
    py="4"
    :_focus="{ shadow: 'outline' }"
    color="gray.500"
    as="nuxt-link"
    to="/figma-plugin-developer"
  >
    <c-flex>
      <c-box w="full">
        <c-heading as="h3" font-size="1.2rem" font-weight="semibold" mb="4" color="vue.500">
          Figma Plugin Developer
        </c-heading>
        <c-text mb="4">
          Help define and build the future of Chakra UI's integration with Figma's design tools.
        </c-text>
        <c-flex mt="4" :flex-dir="['column', 'column', 'row']" spacing="3">
          <c-box d="flex" :mr="[4, 4, null]" :my="[1, 1, 0]" align-items="center">
            <c-icon mr="2" name="briefcase" />
            <c-text font-size="sm">
              Part-time
            </c-text>
          </c-box>
          <c-box d="flex" :mr="[4, 4, null]" :my="[1, 1, 0]" align-items="center">
            <c-icon mr="2" name="map-pin" />
            <c-text font-size="sm">
              Remote
            </c-text>
          </c-box>
          <c-box d="flex" :mr="[4, 4, null]" :my="[1, 1, 0]" align-items="center">
            <c-icon mr="2" name="dollar-sign" />
            <c-text font-size="sm">
              $5,000 per month
            </c-text>
          </c-box>
          <c-box d="flex" :mr="[4, 4, null]" :my="[1, 1, 0]" align-items="center">
            <c-icon mr="2" name="calendar-minus" />
            <c-text font-size="sm">
              Closes on May 28, 2020
            </c-text>
          </c-box>
        </c-flex>
      </c-box>
      <c-box justify="center" align-items="center" :d="['none', 'none', 'flex']">
        <c-icon size="1.5rem" name="chevron-right" />
      </c-box>
    </c-flex>
  </c-link>
</template>

<script>
import { CLink, CHeading, CText, CFlex, CBox, CIcon } from '@chakra-ui/vue'

export default {
  components: { CLink, CHeading, CText, CFlex, CBox, CIcon },
  extends: CLink
}
</script>
