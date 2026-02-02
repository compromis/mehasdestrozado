<template>
  <h1 class="headline">
    {{ $t('intro.heading') }}
  </h1>
</template>

<style lang="scss" scoped>
.headline {
  text-align: center;
  font-family: var(--font-headline);
  text-transform: uppercase;
  font-size: var(--text-5xl);
  letter-spacing: 0;
  padding-block: 4rem;
}

@include media-breakpoint-down(md) { 
  .headline {
    font-size: var(--text-4xl);
    padding-block: 2rem;
  }
}
</style>