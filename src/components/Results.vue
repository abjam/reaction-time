<template>
  <p v-if="showResult">Reaction: {{score}} ms</p>
</template>

<script>
export default {
  props: ['score']
}
</script>

<style>

</style>