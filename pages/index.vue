<template>
    <div>
      <NuxtLayout>
        <NuxtPage/>
      </NuxtLayout>
    </div>
</template>

<script>
useHead({
  bodyAttrs: {
    class: 'body--reset'
  }
})
</script>

<style>
    body--reset {
        margin: 0;
        padding: 0;
    }
</style>