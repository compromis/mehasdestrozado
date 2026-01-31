<template>
  <section class="faq-list">
    <h2>
      Si vols saber-ne més:
    </h2>
    
  <div class="card shadow rounded">
    <details>
      <summary>
        Per què funciona pitjor l’EMT?
      </summary>
      <div>
        <p>El servei d’autobusos de l’EMT està patint un <strong>deteriorament molt greu</strong> des de l’arribada del govern del PP i Vox a l’Ajuntament de València.</p>
        <p>Cada vegada hi ha <strong>més autobusos plens, més temps d’espera, expedicions que es cancel·len</strong> i barris que no reben el servei promés. De mitjana, <strong>prop de 300 autobusos al mes deixen de circular</strong>, cosa que afecta directament el dia a dia de milers de persones.</p>
        <p>Segons dades oficials de l’Empresa Municipal de Transports els seus autobusos circulen hui més lentament que fa dos anys. En només dos anys, l’EMT ha perdut 0,41 km/h de velocitat mitjana, un descens del 3,4% que té un impacte directe en la durada dels trajectes.</p>
        <p>Esta situació té una causa clara: <strong>mala gestió i falta de planificació</strong>. No es cobreixen baixes de conductors ni mecànics, falten recursos humans i fins i tot el Servei Especial per a persones amb mobilitat reduïda està patint retallades.</p>
        <p>L’EMT pot arribar a un forat de 100 milions d’euros: A més, l’EMT arrossega una situació econòmica crítica, amb un deute que supera els 40 milions d’euros i la pèrdua de desenes de milions en ajudes europees i estatals per no complir amb obligacions com la Zona de Baixes Emissions. Tot això posa en risc el futur del servei i pot acabar afectant altres polítiques municipals bàsiques.</p>
        <p>Quan el transport públic es gestiona malament, <strong>qui ho paga és la gent</strong>: la que depén del bus per anar a treballar, estudiar o viure amb autonomia.</p>
      </div>
    </details>
    <details>
      <summary>
        Per què funciona pitjor el Metro?
      </summary>
      <div>
        <p>En els últims dos anys, el servei de <strong>Metrovalencia ha empitjorat de manera evident</strong>. No és una sensació: és el resultat de decisions polítiques concretes del govern del PP i Vox a la Generalitat.</p>
        <p>S’han <strong>reduït vagons i espaiat freqüències</strong>, provocant combois plens, andanes col·lapsades i esperes de més de 15 minuts en moltes línies. Les <strong>avaries són constants</strong>, amb desenes d’incidències cada mes, i en moltes estacions ni tan sols funcionen les pantalles informatives, de manera que la gent no sap quan passarà el pròxim metro.</p>
        <p>A això s’afegeixen <strong>nous validadors més lents</strong>, que generen cues innecessàries, i una deixadesa evident en el manteniment de les instal·lacions. Tot mentre <strong>pugen els preus dels bitllets</strong> i es renuncia a milions d’euros en ajudes al transport públic.</p>
        <p>El problema no és tècnic: és un <strong>model que degrada el transport públic</strong> perquè la gent es canse i acabe agafant el cotxe. I això, en una àrea metropolitana cada vegada més poblada, està portant el sistema al col·lapse.</p>
      </div>
    </details>
    <details>
      <summary>
        La que se’ns ve damunt perquè Maria José Catalá <u>NO VOL</u> aprovar la ZBE:
      </summary>
      <div>
        <p>No aprovar la Zona de Baixes Emissions (ZBE) a València no és una discussió ideològica ni un capritx ecologista. És, sobretot, <strong>un problema de diners i de butxaca</strong>. I els diners, quan falten, sempre acaben eixint del mateix lloc: <strong>de la ciutadania</strong>.</p>
        <p>La llei estatal obliga les ciutats grans a tindre una ZBE en funcionament. No és una opció. És un requisit per poder rebre ajudes públiques destinades al transport i a la mobilitat. Quan València no va complir el termini a finals de 2025, <strong>la primera conseqüència va ser immediata</strong>: l’Ajuntament va haver de tornar <strong>més de 4 milions d’euros</strong> en ajudes al transport públic. Eixos diners ja no tornaran.</p>
        <p>A partir d’ací, el problema es fa més gran. Sense ZBE, València quedava fora de les ajudes estatals per a 2026, que servixen per a mantindre els descomptes en autobusos i abonaments. Açò obligava a prendre una decisió molt clara: <strong>o pujar el preu del transport públic, o pagar-ho amb diners municipals</strong>. L’Ajuntament ha triat pagar-ho, però això significa que <strong>14 milions d’euros ixen del pressupost municipal</strong>, és a dir, dels impostos de totes i tots.</p>
        <p>Això vol dir menys diners per a vivenda, barris, serveis socials, neteja o cultura. Encara que el bitllet no puge, <strong>algú està pagant la factura</strong>, i eixe algú: eres tu amb els teus impostos.</p>
        <p>Però el risc no acaba ací. Moltes inversions importants en carrils bici, reurbanitzacions o projectes de mobilitat sostenible estaven condicionades a tindre la ZBE aprovada. Si no s’implanta, <strong>València pot perdre desenes de milions d’euros</strong> en ajudes ja concedides. I, a més, la llei permet que, si no es complixen les condicions, <strong>no sols s’hagen de tornar eixos diners, sinó pagar multes</strong>.</p>
        <p>Segons els càlculs més prudents, el cost pot ser de <strong>30 milions d’euros</strong>. En l’escenari més negatiu, podria arribar a <strong>més de 100 milions</strong>. Parlem de xifres que poden hipotecar el futur de la ciutat durant anys.</p>
        <p>En resum: no tindre ZBE no evita cap problema, <strong>el multiplica</strong>. No abarateix la vida, l’encarix. O paguem amb bitllets més cars, o paguem amb impostos, o paguem amb serveis pitjors.</p>
      </div>
    </details>
  </div>
  </section>
</template>

<style lang="scss" scoped>
.faq-list {
  max-width: var(--max-width);
  margin: 6rem auto;
  font-size: var(--text-base);

  .card {
    padding: 0;
    overflow: clip;
  }

  h2 {
    font-size: var(--text-xl);
    margin-bottom: 2rem;
    max-width: 800px;
    text-wrap: balance;
  }

  details {
    border-bottom: 1px solid var(--gray-300);

    &:last-child {
      border-bottom: none;
    }

    div {
      padding: 1rem;
      border-top: 1px solid var(--gray-300);
    }
  }

  summary {
    font-weight: bold;
    cursor: pointer;
    padding: 1rem;
    font-size: var(--text-md);

    &:hover {
      background-color: var(--gray-100);
    }
  }
}
</style>