<template>
  <div>
    <HeaderComp />
    <index />
    <FooterComp />
  </div>
</template>

<script>
import HeaderComp from '@/components/HeaderComp.vue' // Ubah "Header" menjadi "HeaderComp"
import index from '@/pages/index.vue'
import FooterComp from '@/components/FooterComp.vue'
export default {
  components: {
    HeaderComp, // Menggunakan "HeaderComp" sebagai alias
    index,
    FooterComp,
  },
}
</script>
