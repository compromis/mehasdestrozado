<template>
  <section v-if="$i18n.locale === 'cas'" class="intro" id="intro">
    <article class="card rounded shadow intro-card">
      <p>El <strong>Metro y la EMT</strong> en València suponen hoy:</p>
      <ul class="arrow-list">
        <li>Esperas eternas.</li>
        <li>No saber si llegarás a tiempo a trabajar o estudiar.</li>
        <li>Buses y vagones saturados en horas punta.</li>
        <li>Buses que pasan de largo porque van llenos.</li>
        <li>Pantallas y relojes que no funcionan o funcionan mal.</li>
        <li>Averías continuas en las vías, las escaleras mecánicas o los accesos.</li>
        <li>… y además: el precio del billete ha subido y subirá.</li>
      </ul>
      <p>Los <strong>gobiernos de PP y VOX han convertido el transporte público en un calvario</strong>. La falta de inversión y una dejadez total repercuten en nuestras vidas, nuestro trabajo, nuestra calidad de vida.</p>
    </article>
    <aside class="video shadow">
      <IntroVideo />
    </aside>
  </section>
   <section v-else class="intro" id="intro">
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