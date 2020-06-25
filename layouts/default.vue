<template>
  <div>
     <page-Header />
    <nuxt />
    <migration />
     <page-footer />
  </div>
</template>

<script>
import PageHeader from '~/components/common/Header.vue'
import Migration from '~/components/common/Migration.vue'
import PageFooter from '~/components/common/PageFooter.vue'
export default {
  components: {
    PageHeader,
    Migration,
    PageFooter
  
 }
}
</script>