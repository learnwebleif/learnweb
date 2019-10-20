<style>
  @import url("https://fonts.googleapis.com/css?family=Quicksand|Ubuntu&display=swap");

  img {
    display: flex;
    margin-bottom: 5rem;
    max-width: 60%;
    margin: auto;
    padding: 2rem;
  }
  .contact-button {
    margin-top: 2rem;
  }

  .ingress {
    font-weight: 400;
    font-size: 21px;
    line-height: 32px;
    color: #606f94;
    margin-bottom: 5rem;
  }

  @media (min-width: 40rem) {
    img {
      display: flex;
      margin-bottom: 5rem;
      max-width: 100%;
    }
    h1 {
      margin-top: 4rem;
    }
    p {
      font-family: "Quicksand", sans-serif;
    }
    .lms {
      display: flex;
      align-content: center;
      margin: auto;
      justify-content: space-evenly;
      margin-top: 4rem;
    }
    .scormcloud {
      width: 200px;
      padding-left: 5rem;
      margin: 0;
    }
    .itslearning {
      width: 130px;
    }
    .canvas {
      width: 130px;
    }
    .moodle {
      width: 130px;
    }

    .vuepress {
      width: 200px;
    }
  }
</style>

<svelte:head>
  <title>Pedagogik</title>
</svelte:head>

<p class="ingress">
  Med hjälp av standarder som LTI och SCORM kan även pedagoger och ämnesexperter
  skapa innehåll. Vi har effektiva verktyg och metoder som gör det möjligt att
  skapa interaktivt innehåll oavsett vilket LMS som används. Vissa LMS kan
  importera SCORM-objekt direkt annars kan lösningen vara att använda LTI.
</p>

<div class="scormcloud">
  <a href="https://rusticisoftware.com/products/scorm-cloud/">
    <img src="scormcloud.png" alt="Scorm-cloud" />
  </a>
</div>

<p>
  Alla LMS har begränsade möjligheter att skapa ett interaktivt innehåll som
  stimulerar till lärande. Läromedelsproducenter kan använda standarder som
  t.ex. LTI för att koppla lärreseurser till kurser i ett LMS men de flesta har
  valt att skapa egna system vilket försvårar tillgängligheten och skapar en
  negativ användarupplevelse. Genom ett samarbete mellan pedagoger och
  webbutvecklare finns nu fantastiska möjligheter att skapa framtidens digitala
  resurser.
</p>

<div class="lms">
  <div class="itslearning">
    <img src="itslearning.png" alt="itslearning" />
  </div>
  <div class="canvas">
    <img src="canvas.png" alt="Canvas" />
  </div>
  <div class="moodle">
    <img src="moodle.jpg" alt="Moodle" />
  </div>
</div>

<h1 style="margin-top: 3rem;">Manus</h1>

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
