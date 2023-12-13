<template>
  <div>
    <slot name="header"/>
    <div>
      <img src="https://w7.pngwing.com/pngs/485/422/png-transparent-warning-alert-error-thumbnail.png"
           alt=""/>
    </div>
    <slot name="redirectEl"/>
  </div>
</template>

<style scoped>
img{
  width: 7rem;
}
</style>