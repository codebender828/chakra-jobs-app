<template>
  <container bg="gray.50" py="6" as="main">
    <c-heading mb="6" font-weight="bold">
      Job Listings
    </c-heading>
    <job-card />
  </container>
</template>

<script>
import { CHeading } from '@chakra-ui/vue'
import Container from '@/components/container'
import JobCard from '@/components/job-card'

export default {
  name: 'HomePage',
  components: {
    CHeading,
    Container,
    JobCard
  }
}
</script>
