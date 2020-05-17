<template>
  <container as="section">
    <c-grid :template-columns="['1fr', '1fr', '1fr 2fr']">
      <c-box
        :d="['none', 'none', 'block']"
        pt="10"
        :grid-column="[null, null, '1/2']"
      >
        <c-box
          as="aside"
          pos="sticky"
          top="10"
          color="gray.500"
          bg="gray.100"
          rounded="lg"
          p="8"
        >
          <c-flex align-items="start" border-bottom="2px solid" py="3" border-color="gray.200">
            <c-icon mr="2" name="briefcase" />
            <c-box :mt="-0.8">
              <c-text color="gray.800" font-size="0.9em">
                Part-time
              </c-text>
            </c-box>
          </c-flex>
          <c-flex align-items="start" border-bottom="2px solid" py="3" border-color="gray.200">
            <c-icon mr="2" name="map-pin" />
            <c-box :mt="-0.8">
              <c-text color="gray.800" font-size="0.9em">
                Remote
              </c-text>
              <c-text color="gray.500" font-size="0.9em">
                Asia Pacific / Africa
              </c-text>
            </c-box>
          </c-flex>
          <c-flex align-items="start" border-bottom="2px solid" py="3" border-color="gray.200">
            <c-icon mr="2" name="dollar-sign" />
            <c-box :mt="-0.8">
              <c-text color="gray.800" font-size="0.9em">
                $5,000 per month
              </c-text>
              <c-text color="gray.500" font-size="0.9em">
                Conversion is done in the final currency
              </c-text>
            </c-box>
          </c-flex>
          <c-flex align-items="start" py="3">
            <c-icon mr="2" name="calendar-minus" />
            <c-box :mt="-0.8">
              <c-text color="gray.800" font-size="0.9em">
                Closes on May 28, 2020
              </c-text>
            </c-box>
          </c-flex>
          <c-button mt="3" bg="black" :_hover="{ bg: 'gray.700' }" :_active="{ bg: 'gray.800' }" color="white">
            Apply for this job
          </c-button>
        </c-box>
      </c-box>
      <c-box as="main" py="10" :px="[null, null, 10]" color="gray.600" :grid-column="['1/2', '1/2', '2/3']">
        <c-link
          d="inline-flex"
          align-items="center"
          mb="3"
          font-family="body"
          as="nuxt-link"
          to="/"
        >
          <c-icon name="chevron-left" mr="1" />
          Return to listings
        </c-link>
        <c-heading>Figma Plugin Developer</c-heading>
        <c-text color="gray.500" font-size="1.2em" mt="3" as="blockquote">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.
        </c-text>
        <c-box
          as="aside"
          color="gray.500"
          mt="8"
          px="4"
          :d="['block', 'block', 'none']"
        >
          <c-flex align-items="start" border-bottom="2px solid" py="3" border-color="gray.200">
            <c-icon mr="2" name="briefcase" />
            <c-box :mt="-0.8">
              <c-text color="gray.800" font-size="0.9em">
                Part-time
              </c-text>
            </c-box>
          </c-flex>
          <c-flex align-items="start" border-bottom="2px solid" py="3" border-color="gray.200">
            <c-icon mr="2" name="map-pin" />
            <c-box :mt="-0.8">
              <c-text color="gray.800" font-size="0.9em">
                Remote
              </c-text>
              <c-text color="gray.500" font-size="0.9em">
                Asia Pacific / Africa
              </c-text>
            </c-box>
          </c-flex>
          <c-flex align-items="start" border-bottom="2px solid" py="3" border-color="gray.200">
            <c-icon mr="2" name="dollar-sign" />
            <c-box :mt="-0.8">
              <c-text color="gray.800" font-size="0.9em">
                $5,000 per month
              </c-text>
              <c-text color="gray.500" font-size="0.9em">
                Conversion is done in the final currency
              </c-text>
            </c-box>
          </c-flex>
          <c-flex align-items="start" py="3">
            <c-icon mr="2" name="calendar-minus" />
            <c-box :mt="-0.8">
              <c-text color="gray.800" font-size="0.9em">
                Closes on May 28, 2020
              </c-text>
            </c-box>
          </c-flex>
        </c-box>
        <br>
        <c-text>
          Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
        </c-text>
        <br>
        <c-heading as="h4" font-size="xl">
          Vel quam elementum
        </c-heading>
        <c-text my="2">
          Aenean euismod elementum nisi quis eleifend quam adipiscing vitae proin. Mattis molestie a iaculis at. Nunc aliquet bibendum enim facilisis. Pharetra massa massa ultricies mi quis hendrerit dolor magna eget.
        </c-text>
        <c-text my="2">
          Nec feugiat in fermentum posuere urna nec tincidunt. Imperdiet massa:
        </c-text>
        <c-list style-type="none" font-family="body">
          <c-list-item :class="listItemClass" d="block">
            Laoreet id donec ultrices tincidunt arcu non. Amet nisl suscipit adipiscing bibendum.
          </c-list-item>
          <c-list-item :class="listItemClass" d="block">
            Lacus sed viverra tellus in hac. Vitae nunc sed velit dignissim sodales ut eu sem integer.
          </c-list-item>
          <c-list-item :class="listItemClass" d="block">
            Lacus sed viverra tellus in hac. Pellentesque elit ullamcorper.
          </c-list-item>
          <c-list-item :class="listItemClass" d="block">
            Sed arcu non odio euismod lacinia at.
          </c-list-item>
        </c-list>
        <c-text my="2">
          ... velit ut tortor pretium viverra. In massa tempor nec feugiat nisl.
        </c-text>
        <br>
        <c-text my="2">
          Aenean euismod elementum nisi quis eleifend quam adipiscing vitae proin. Mattis molestie a iaculis at. Nunc aliquet bibendum enim facilisis. Pharetra massa massa ultricies mi quis hendrerit dolor magna eget.
        </c-text>
        <c-list style-type="none" font-family="body">
          <c-list-item :class="listItemClass" d="block">
            Laoreet id donec ultrices tincidunt arcu non. Amet nisl suscipit adipiscing bibendum.
          </c-list-item>
          <c-list-item :class="listItemClass" d="block">
            Lacus sed viverra tellus in hac. Vitae nunc sed velit dignissim sodales ut eu sem integer.
          </c-list-item>
          <c-list-item :class="listItemClass" d="block">
            Lacus sed viverra tellus in hac. Pellentesque elit ullamcorper.
          </c-list-item>
          <c-list-item :class="listItemClass" d="block">
            Sed arcu non odio euismod lacinia at.
          </c-list-item>
        </c-list>
        <c-button mt="6" bg="black" :_hover="{ bg: 'gray.700' }" :_active="{ bg: 'gray.800' }" color="white">
          Apply for this job
        </c-button>
      </c-box>
    </c-grid>
  </container>
</template>

<script>
import { Css, CGrid, CBox, CFlex, CIcon, CLink, CButton, CHeading, CText, CList, CListItem } from '@chakra-ui/vue'
import { css } from 'emotion'
import Container from '@/components/container'

export default {
  components: { Container, CGrid, CBox, CFlex, CIcon, CText, CHeading, CButton, CList, CListItem, CLink },
  extends: Container,
  inject: ['$chakraTheme'],
  computed: {
    theme: vm => vm.$chakraTheme(),
    listItemClass () {
      const _class = css(Css({
        pl: '1.25rem',
        pos: 'relative',

        ':before': {
          content: '""',
          pos: 'absolute',
          left: '.125rem',
          top: '.625rem',
          d: 'block',
          h: '.375rem',
          w: '.375rem',
          rounded: 'full',
          bg: this.theme.colors.gray[400]
        }
      })(this.theme))
      return _class
    }
  }
}
</script>
