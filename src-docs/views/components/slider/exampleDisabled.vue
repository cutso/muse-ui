<template>
<div>
  <mu-slider v-model="value1" disabled class="demo-slider"/>
  <mu-slider v-model="value2" disabled class="demo-slider"/>
  <mu-slider v-model="value3" disabled class="demo-slider"/>
</div>
</template>

<script>
export default {
  data () {
    return {
      value1: 0,
      value2: 50,
      value3: 100
    }
  }
}
</script>

<style lang="css">
.demo-slider {
  margin-bottom: 16px;
}
</style>
