<template>
  <div class="center">
    <left-content></left-content>
    <center-content></center-content>
    <right-content></right-content>
    <bottom></bottom>
  </div>
</template>

<script>
import LeftContent from 'cpnts/left-content/left-content'
import CenterContent from 'cpnts/center-content/center-content'
import RightContent from 'cpnts/right-content/right-content'
import Bottom from 'cpnts/bottom/bottom'
export default {
  components: {
    LeftContent,
    CenterContent,
    RightContent,
    Bottom
  },
  props: {},
  data () {
    return {
    }
  },
  watch: {},
  computed: {},
  methods: {},
  created () {},
  mounted () {}
}
</script>
<style lang="scss" scoped>
.center{
  position: relative;
  display: flex;
  align-items:flex-start;
  height: 100%;
  width: 90%;
  margin: calc(var(--margin) * 1px) auto;
  @media screen and (max-width:1200px){
    width: 96%;
  }
}
</style>
