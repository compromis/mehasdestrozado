<template>
  <section v-if="$i18n.locale === 'cas'" class="faq-list">
    <h2>
      ¿Qué proponemos desde Compromís?
    </h2>
    
  <div class="card shadow rounded">
    <p><strong>Para el metro, exigimos:</strong></p>
    <ul class="arrow-list">
      <li>Un plan de choque urgente para mejorar frecuencias y fiabilidad.</li>
      <li>Más vagones y más personal, no menos.</li>
      <li>Inversión real en mantenimiento e información en las estaciones.</li>
      <li>La planificación de nuevas líneas que conecten municipios como Xirivella, Alaquàs o Aldaia con València. También impulsar las nuevas líneas 11 y 12 y la ampliación de la 10.</li>
      <li>Una gestión profesional que ponga a las personas usuarias en el centro.</li>
    </ul>
    <p><strong>Para la EMT, defendemos:</strong></p>
    <ul class="arrow-list">
      <li>Recuperar todas las expediciones canceladas y reforzar las líneas saturadas.</li>
      <li>Cubrir bajas y ampliar plantillas de conductores y mecánicos.</li>
      <li>Garantizar el Servicio Especial para personas con movilidad reducida.</li>
      <li>Poner orden en la situación económica con transparencia y una auditoría independiente en la EMT.</li>
      <li>Asegurar todas las ayudas posibles al transporte público, cumpliendo con las obligaciones ambientales.</li>
    </ul>
  </div>
  </section>
  <section v-else class="faq-list">
    <h2>
      Què proposem des de Compromís?
    </h2>
    
  <div class="card shadow rounded">
    <p>Anem a ser clars: Per a Compromís la vivenda i el transport públic son dos dels grans temes que <strong>s’han d’abordar ja i amb valentia</strong>. Entenem el transport públic <strong>no com un problema, sinó com una solució</strong>. I per això proposem un canvi de rumb immediat basat en inversió, planificació i bona gestió.</p>
    <p><strong>Per al metro</strong>, exigim:</p>
    <ul class="arrow-list">
      <li><div>Un <strong>pla de xoc urgent</strong> per millorar freqüències i fiabilitat.</div></li>
      <li><div><strong>Més vagons i més personal</strong>, no menys.</div></li>
      <li><div><strong>Inversió real en manteniment i informació a les estacions</strong>.</div></li>
      <li><div>La <strong>planificació de noves línies</strong> que connecten municipis com Xirivella, Alaquàs o Aldaia amb València. També impulsar les noves línies 11 i 12 i l’ampliació de la 10.</div></li>
      <li><div>Una gestió professional que pose les persones usuàries al centre.</div></li>
    </ul>
    <p><strong>Per a l’EMT</strong>, defensem:</p>
    <ul class="arrow-list">
      <li><div>Recuperar totes les <strong>expedicions cancel·lades</strong> i reforçar les línies saturades.</div></li>
      <li><div><strong>Cobrir baixes i ampliar plantilles</strong> de conductors i mecànics.</div></li>
      <li><div>Garantir el <strong>Servei Especial</strong> per a persones amb mobilitat reduïda.</div></li>
      <li><div>Posar ordre a la situació econòmica amb <strong>transparència i una auditoria independent a l’EMT</strong>.</div></li>
      <li><div>Assegurar totes les <strong>ajudes possibles al transport públic</strong>, complint amb les obligacions ambientals.</div></li>
    </ul>
    <p>En definitiva, volem un <strong>transport públic fiable, assequible i de qualitat</strong>, que connecte barris i municipis, reduïsca el trànsit i millore la vida de la gent.</p>
  </div>
  </section>
</template>

<style lang="scss" scoped>
.faq-list {
  max-width: var(--max-width);
  margin: 6rem auto;
  font-size: var(--text-base);

  h2 {
    font-size: var(--text-xl);
    margin-bottom: 2rem;
    max-width: 800px;
    text-wrap: balance;
  }
}
</style>