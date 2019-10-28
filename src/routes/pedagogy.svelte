<style>
  @import url("https://fonts.googleapis.com/css?family=Quicksand|Ubuntu&display=swap");

  img {
    display: flex;
    margin-bottom: 5rem;
    max-width: 60%;
    margin: auto;
    padding: 2rem 0;
  }
  .contact-button {
    margin-top: 2rem;
  }

  a:after {
    padding-left: 0.5rem;
    content: url("arrow-2.svg");
  }

  .card-footer {
    text-align: center;
    margin-bottom: 2rem;
  }

  .ingress {
    margin-bottom: 2rem;
  }

  a {
    text-decoration: none;
  }

  @media (min-width: 40rem) {
    .contact-button {
      text-align: right;
    }

    .card {
      margin-top: 4rem;
      margin-bottom: 3rem;
      margin-left: 3rem;
      -webkit-box-direction: normal;
      font-size: 62.5%;
      font-family: Camphor, Open Sans, Segoe UI, sans-serif;
      font-weight: 400;
      font-style: normal;
      -webkit-font-smoothing: antialiased;
      text-rendering: optimizeLegibility;
      font-feature-settings: "pnum";
      font-variant-numeric: proportional-nums;
      box-sizing: border-box;
      background: #fff;
      will-change: transform;
      border-radius: 6px;
      position: relative;
      width: 55%;
      transform-origin: 50% 100%;
      transform: scale(1);
      opacity: 1;
      transition: transform 0.4s ease-in-out, box-shadow 0.4s ease-in,
        opacity 0.2s;
      box-shadow: 0 13px 27px -5px rgba(50, 50, 93, 0.25),
        0 8px 16px -8px rgba(0, 0, 0, 0.3),
        0 -6px 16px -6px rgba(0, 0, 0, 0.025), 0 0 20px rgba(0, 0, 0, 0.04);
    }

    .card-footer {
      display: flex;
      justify-content: center;
      align-content: center;
      background: #f6f9fc;
      margin-bottom: 5rem;
    }

    .card-link {
      color: #6772e5;
      font-weight: 500;
      transition: color 0.1s ease;
      cursor: pointer;
      padding: 16px 34px 22px;
      width: 100%;
      text-align: center;
      font-size: 15px;
      line-height: 28px;
    }

    img {
      display: flex;
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
      margin: auto;
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
      width: 150px;
    }
  }
</style>

<svelte:head>
  <title>Pedagogik</title>
</svelte:head>

<p class="ingress">
  Alla LMS har begränsade möjligheter att skapa ett interaktivt innehåll som
  stimulerar till lärande. Med hjälp av standarder som LTI och SCORM kan även
  pedagoger och ämnesexperter skapa rikt interaktivt innehåll.
</p>

<div class="card">
  <div class="scormcloud">
    <img src="scormcloud.png" alt="Scorm-cloud" />
  </div>
  <div class="card-footer">
    <a
      class="card-link"
      href="https://rusticisoftware.com/products/scorm-cloud/">
      SCORM Cloud
    </a>
  </div>
</div>

<p>
  Vissa läromedelsproducenter använder standarder som t.ex. LTI för att koppla
  lärreseurser till kurser i ett LMS men de flesta har valt att skapa egna
  system vilket försvårar tillgängligheten och skapar en negativ
  användarupplevelse.
</p>
<p>
  Genom ett samarbete mellan pedagoger och webbutvecklare finns nu fantastiska
  möjligheter att skapa framtidens digitala resurser.Vi har effektiva verktyg
  och metoder som gör det möjligt att skapa innehåll oavsett vilket LMS som
  används. Vissa LMS kan importera SCORM-objekt direkt annars kan lösningen vara
  att använda LTI. Vi har erfarenhet att arbeta med t.ex. itslearning, Canvas
  och Moodle.
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

<div class="card">
  <div class="scormcloud">
    <img class="vuepress" src="vuepress.png" alt="Vuepress" />
  </div>
  <div class="card-footer">
    <a class="card-link" href="webdesign">Läs mer</a>
  </div>
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
