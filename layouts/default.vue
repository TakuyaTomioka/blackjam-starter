<template>
  <div>
    <Header />
    <main>
      <nuxt/>
    </main>
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import SwiperItemVue from '../components/SwiperItem.vue'

export default {
  components: {
    Header
  }
}
</script>

<style lang="stylus">
@font-face 
  font-family 'Product Sans'
  font-style normal
  font-weight 400
  font-display swap
  src local('Open Sans'), local('OpenSans'), url(https://fonts.gstatic.com/s/productsans/v5/HYvgU2fE2nRJvZ5JFAumwegdm0LZdjqr5-oayXSOefg.woff2) format('woff2')
html 
  font-family 'Product Sans', 'Yu Gothic', 'YuGothic', sans-serif
  color #555
body 
  margin 0
  overflow-x hidden
  font-size 15px
main 
  width 100%
  max-width 1000px
  margin 100px auto 100px
  position relative
:link,
:visited 
  color inherit
  font-weight bold
  text-decoration none
::-webkit-scrollbar 
  width 8px
::-webkit-scrollbar-track
  background #eee
::-webkit-scrollbar-thumb 
  background #555
@media (max-width: 768px) 
  main 
    margin-top 0
</style>

