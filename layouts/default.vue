<template>
  <div class="flex w-full flex-col">
    <AppHeader />
    <slot />
    <AppFooter />
  </div>
</template>
<style lang="scss">
body {
  padding: 0px;
  margin: 0px;
}
</style>