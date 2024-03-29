<script lang="ts">
  export default defineNuxtComponent({
    mounted() {
      console.log(this.$config.public.msg)
    }
  })
</script>

<template>
  <div>
    {{ $config.public.msg }}
  </div>
</template>

<style lang="scss"></style>