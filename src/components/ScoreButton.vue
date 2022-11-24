<template>
  <v-btn class="ma-1">{{ value }}</v-btn>
</template>

<script>
export default {
  props: ['value'],
  setup(props) {
    console.log(props)
  }
}
</script>
