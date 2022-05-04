<template>
  <div>
    <IndexHeader/>
    <IndexAboute style="margin-top:700px" />
    <IndexEvent/>
    <IndexBits/>
    <IndexCarousel/>
    <ShopCarousel/>
    <IndexPayInfo class="q-mt-xl"/>
    <IndexFooter/>
  </div>
</template>
<script>
import IndexHeader from 'src/components/IndexHeader'
import IndexAboute from 'src/components/IndexAboute'
import IndexEvent from 'src/components/IndexEvent'
import IndexBits from 'src/components/IndexBits'
import IndexCarousel from 'src/components/IndexCarousel.vue'
import ShopCarousel from 'src/components/ShopCarousel.vue'
import IndexPayInfo from 'src/components/IndexPayInfo.vue'
import IndexFooter from 'src/components/IndexFooter.vue'
export default {
  components: {
    IndexHeader,
    IndexAboute,
    IndexEvent,
    IndexBits,
    IndexCarousel,
    ShopCarousel,
    IndexPayInfo,
    IndexFooter
},

}
</script>
<style lang="">

</style>
