<template>
  <section class="intro" id="intro">
    <article class="card rounded shadow intro-card">
      <p>El <strong>Metro i EMT</strong> a València suposen hui:</p>
      <ul class="arrow-list">
        <li>Esperes eternes.</li>
        <li>No saber si arribaràs a temps a treballar o estudiar.</li>
        <li>Busos i vagons saturats en hores punta.</li>
        <li>Busos que passen de llarg perquè van plens.</li>
        <li>Pantalles i rellotges que no funcionen o funcionen malament.</li>
        <li>Avaries contínues en les vies, les escales mecàniques o els accessos.</li>
        <li>... i a més: el preu del bitllet ha pujat i pujarà.</li>
      </ul>
      <p>Els <strong>governs de PP i VOX han convertit moure’s en transport públic en un calvari</strong>. La manca d’inversió i una deixadesa total repercuteixen en les nostres vides, la nostra feina, la nostra qualitat de vida. </p>
    </article>
    <aside class="video shadow">
      <IntroVideo />
    </aside>
  </section>
  <div class="trailing">
    {{ $t('intro.trailing') }}
  </div>
</template>

<style lang="scss" scoped>
.intro {
  margin: calc(2rem + 5vh) 0;
  display: grid;
  grid-template-columns: 2.5fr 1fr;
  gap: 1rem;
}

.video {
  width: 100%;
  background: var(--gray-900);
  overflow: hidden;
  border-radius: 1rem;
  position: relative;

  iframe {
    display: block;
    height: 100%;
    width: 100%;
    aspect-ratio: 9 / 16;
  }
}

.intro-card {
  font-size: clamp(1.25rem, 0.45vi + 1.15rem, 1.75rem);
}

.trailing {
  text-align: center;
  font-family: var(--font-headline);
  text-transform: uppercase;
  font-size: var(--text-5xl);
  letter-spacing: 0;
  padding-block: 4rem;
  line-height: 1;
}


@media (max-width: 1200px) {
  .intro {
    grid-template-columns: 1fr;
  }
}
</style>