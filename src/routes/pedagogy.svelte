<style>
  @import url("https://fonts.googleapis.com/css?family=Quicksand|Ubuntu&display=swap");
  img {
    display: flex;
    margin-top: 4rem;
    margin-bottom: 5rem;
    max-width: 100%;
  }
  .contact-button {
    margin-top: 2rem;
  }

  @media (min-width: 40rem) {
    img {
      display: block;
      margin-top: 4rem;
      margin-bottom: 5rem;
    }
    h1,
    h2 {
      font-family: "Quicksand", sans-serif;
      margin-top: 4rem;
    }
    p {
      font-family: "Quicksand", sans-serif;
    }
    .vuepress, .lms {
      width: 30%;
    }
  }
</style>

<svelte:head>
  <title>Pedagogik</title>
</svelte:head>

<p>
  Ett bra innehåll och en tydlig struktur är alltid grunden för ett lyckat
  genomförande av en utbildning. Vi har lång erfarenhet av samarbeten med
  pedagoger och ämnesexperter. Alla LMS, LSX och andra lärsystem är
  webbapplikationer och eftersom vi är webbutvecklare är det vår hemmaplan. Vi
  kan garantera att er organisation kan få ut maximalt av en digital satsning
  oavsett om det handlar om att utveckla digitalt innehåll, utbildning eller
  support.
</p>

<h2>Learning Management systems</h2>

<p>
  Alla LMS har begränsade möjligheter att skapa ett interaktivt innehåll som
  stimulerar till lärande. Läromedelsproducenter kan använda standarder som
  t.ex. LTI för att koppla lärreseurser till kurser i ett LMS men de flesta har
  valt att skapa egna system vilket försvårar tillgängligheten och skapar en
  negativ användarupplevelse.
</p>

<p>
  Med hjälp av standarder som LTI och SCORM kan även pedagoger och ämnesexperter
  skapa innehåll. Vi har effektiva verktyg och metoder som gör det möjligt att
  skapa interaktivt innehåll oavsett vilket LMS som används. Vissa LMS kan
  importera SCORM-objekt direkt annars kan lösningen vara att använda LTI.
</p>

<!-- <img width="100%" src="lms.png" alt="LMS" /> -->
<div class="lms">
  <img src="lms.png" alt="LMS" />
</div>

<h1>Manus</h1>

<p>
  Webbutveckling är en sak, mediaproduktion, film, bilder etc. är en annan, sen
  kommer också manusskrivande på detta. Det är många olika färdigheter en
  pedagog ska behärska för att kunna använda digital teknik på ett sätt som
  skapar mervärde i en utbildning. Vi har en enkel och tydlig strategi som inte
  kräver några förkunskaper av en pedagog men vi utgår naturligtvis från den
  kompetens som finns.
</p>

<p>
  Man kan börja med att skriva manus i t.ex. Word men annars är Markdown ett
  format som passar bra för webben. Markdown kan man använda utan några
  förkunskaper.
</p>

<p>
  Man kan skapa både teknisk dokumentation och e-kurser med Markdown. Vill man
  sedan utveckla innehållet mot e-learning med t.ex. Adapt, LMS, eller MOOC är
  det inte några problem eftersom Markdown genererar html-filer.
</p>

<p>
  För teknisk dokumentation använder vi Vuepress där Markdown används för att
  skapa innehållet. Slutresultatet kan publiceras på Intranätet, en webbplats
  eller ett LMS.
</p>

<p>
  <a href="webdesign">Läs mer</a>
  om Vuepress och teknisk dokumentation.
</p>

<div class="vuepress">
  <img src="vuepress.png" alt="Vuepress" />
</div>

<h1>Kurs i webbpedagogik</h1>

<p>
  Vi vill gärna erbjuda pedagoger och ämnesexperter utbildning i webbutveckling
  och mediaproduktion för webben. Vi har ett färdigt upplägg som kan anpassas
  efter individuella önskemål.
</p>

<div
  style="display: flex; justify-content: center; margin-top: 3rem;
  margin-bottom: 4rem;" />

<div class="contact-button">
  <a href="contact">
    <button id="send">Kontakta oss</button>
  </a>
</div>
