<template>
  <tr>
    <td width="40">{{ number + '.' }}</td>
    <td width="18"><img v-if="spicy == true" src="~assets/images/spicy.gif"></td>
    <td width="400">{{ english }} &nbsp; &nbsp; &nbsp; {{ chinese }}</td>
    <td width="70" align="right">{{ price }}</td>
  </tr>
</template>

<script>
export default {
  name: 'LunchItem',
  props: {
    number: String,
    spicy: Boolean,
    english: String,
    chinese: String,
    price: String
  }
}
</script>

<style scoped>
tr { line-height: 30px; }
td { vertical-align: top; }
img {
  height: 18px;
  padding-bottom: 4px;
}
</style>

