<!--
 * @Author: your name
 * @Date: 2021-02-03 08:46:07
 * @LastEditTime: 2021-02-03 14:43:23
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /vuetest/src/views/addEventListener.vue
-->
<template>
  <div>axios</div>
</template>

<script>
export default {
  data(){
    return{
      testData: 0
    }
  },
  mounted () {
    this.init()
  },
  methods: {
    init () {
      window.addEventListener('click',() => {
        this.testData = 123
      })
    }
  }
}
</script>
