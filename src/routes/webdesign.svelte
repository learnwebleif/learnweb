<style>
  @import url("https://fonts.googleapis.com/css?family=Quicksand|Ubuntu&display=swap");

  /* img {
    display: flex;
    margin-top: 3rem;
    margin-bottom: 5rem;
    width: 50%;
  } */

  img {
    display: flex;
    margin-bottom: 5rem;
    margin: auto;
    padding: 1rem 0;
  }

  #svelte-img {
    width: 200px;
  }

  #vue-img {
    width: 200px;
  }

  #bulma-img {
    width: 200px;
  }

  #tailwind-img {
    width: 200px;
  }

  #adapt {
    width: 200px;
  }

  #e-course {
    width: 260px;
  }

  #demo {
    width: 260px;
  }

  #vuepress {
    width: 200px;
  }

  #talsynt1 {
    width: 100px;
  }

  #talsynt2 {
    width: 200px;
  }

  .ingress {
    margin-bottom: 2rem;
  }

  .contact-button {
    margin-top: 2rem;
  }

  #contact:after {
    padding-left: 0.5rem;
    content: url("arrow-2.svg");
  }

  .card-footer {
    text-align: center;
    margin-bottom: 2rem;
  }

  .accesibility-2 {
    min-width: 60% !important;
  }

  .contact-button {
    margin-top: 2rem;
  }

  figure {
    margin: 0;
  }

  figure > img {
    margin: 0;
    width: 100%;
  }

  .e-course {
    margin: 4rem 0;
  }

  .accesibility {
    display: block;
  }

  @media (min-width: 40rem) {
    #talsynt1 {
      width: 200px;
    }

    #talsynt2 {
      width: 400px;
    }

    .contact-button {
      text-align: right;
    }

    #e-course {
      width: 460px;
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

    figcaption {
      margin-top: 1rem;
    }

    img {
      display: flex;
      max-width: 100%;
    }

    .adapt {
      width: 200px;
      margin: auto;
    }

    .vuepress-card {
      width: 200px;
      margin: auto;
    }

    h1 {
      margin-top: 10rem;
    }

    h1,
    h2 {
      font-family: "Quicksand", sans-serif;
    }

    p {
      font-family: "Quicksand", sans-serif;
    }

    .framework {
      display: flex;
      justify-content: space-between;
      margin-top: 1rem;
      margin-bottom: 2rem;
    }

    #svelte-img {
      width: 18%;
      height: 50px;
    }

    #vue-img {
      width: 18%;
      height: 60px;
    }

    #bulma-img {
      width: 18%;
      height: 50px;
    }

    #tailwind-img {
      width: 25%;
      height: 50px;
    }

    .adapt,
    .vuepress,
    .accesibility-1 {
      width: 30%;
    }

    .accesibility-2 {
      width: 50%;
    }

    .accesibility {
      display: flex;
    }

    .multiple-choice {
      width: 50%;
    }

    .e-course {
      width: 80%;
    }
  }
</style>

<svelte:head>
  <title>Webbutveckling</title>
</svelte:head>

<p class="ingress">
  Vi bygger appar med arkitekturen
  <a href="https://jamstack.org/">JAMstack</a>
  och standarden SCORM vilket gör att apparna inte blir beroende av någon
  specifik databas eller server. Vi använder idag främst
  <a href="https://svelte.dev">Svelte</a>
  och
  <a href="https://vuejs.org/">Vue</a>
  kombinerat med
  <a href="https://bulma.io/">Bulma</a>
  eller
  <a href="https://tailwindcss.com/">tailwindcss</a>
  men kan naturligtvis använda andra ramverk eller bara ren html, css och
  javascript för specifika önskemål.
</p>

<div class="framework">
  <img id="svelte-img" src="svelte.png" alt="Svelte" />
  <img id="vue-img" src="vue.png" alt="Vue" />
  <img id="bulma-img" src="bulma.png" alt="Bulma" />
  <img id="tailwind-img" src="tailwind.png" alt="Tailwind" />
</div>

<h1>E-learning</h1>

<p>
  För traditionell e-learning använder vi
  <a href="https://www.adaptlearning.org/">Adapt</a>
  . Med Adapt får man SCORM-funktionalitet vilket gör att man kan kommunicera
  med ett LMS för att spara t.ex. progression eller resultat från ett test etc.
</p>
<!-- <p>
  <a href="pedagogy">Läs mer</a>
  om SCORM och LMS.
</p> -->

<div class="card">
  <div class="adapt">
    <img id="adapt" src="adapt.png" alt="adapt" />
  </div>
  <div class="card-footer">
    <a class="card-link" href="https://www.adaptlearning.org/">Adapt</a>
  </div>
</div>

<h1>Teknisk dokumentation</h1>

<p>
  För teknisk dokumentation använder vi Vuepress som är en "Vue-powered Static
  Site Generator". Vuepress använder Markdown för att skapa huvuddelen av
  innehållet vilket gör det oerhört enkelt och kostnadseffektivt producera
  innehåll men det finns även en möjlighet att använda Vue för mer avancerade
  funktioner.
</p>

<div class="card">
  <div class="vuepress-card">
    <img id="vuepress" src="vuepress.png" alt="Vuepress" />
  </div>
  <div class="card-footer">
    <a class="card-link" href="https://vuepress.vuejs.org/">Vuepress</a>
  </div>
</div>

<h1>Tillgänglighet</h1>

<p>
  För att göra innehållet tillgängligt för så många som möjligt försöker vi
  arbeta med semantisk html, talsyntes, responsiv design samt optimerar
  innehållet för långsamma nätverk.
</p>

<div class="accesibility">
  <div class="accesibility-1">
    <img id="talsynt1" src="talsyntes.png" alt="Tillgänglighet" />
  </div>
  <div class="accesibility-2">
    <img id="talsynt2" src="responsiv.png" alt="Tillgänglighet" />
  </div>
</div>

<!-- <div style="margin-bottom: 7rem; margin-top: 3rem">
  <h1>Webbpedagogik</h1>

  <p>
    Vi har under 20 års tid arbetat tillsammans med pedagoger. Det finns inte
    någon magisk formel eller metod som garanterar ett bra slutresultat men just
    kombinationen av webbutveckling och pedagogik tycker vi är spännande oavsett
    om man har ett team av webbutvecklare och pedagoger eller om man arbetar med
    utbildning och support för pedagoger eller ämnesexperter.
  </p>

  <p>
    <a href="https://learnweb.se/pedagogy">Läs mer</a>
    om webbpedagogik.
  </p>
</div> -->

<h1 style="margin-top: 6rem;">Exempelprojekt</h1>

<div style="margin-bottom: 3rem;">
  <p>Multiple choice utvecklad i Svelte.</p>
  <div class="demo-button">
    <a href="https://multiple-choice.learnwebleif.now.sh/">
      <button id="send">Demo</button>
    </a>
  </div>
  <br />
  <div class="multiple-choice">
    <img id="demo" src="mc.png" alt="Multiple choice" />
  </div>
</div>

<h1>E-kurser</h1>

<p>
  Vi har utvecklat hundratals e-kurser och digitala resureser genom åren med
  olika budgetar vilket gör att vi kan få ut det mesta av både stora och små
  projekt. Här är några exempel.
</p>

<div class="e-course">
  <figure>
    <img id="e-course" src="stom-ex.png" alt="exempel på e-kurs" />
    <figcaption>Stöd- och matchningstjänst</figcaption>
  </figure>
</div>

<div class="e-course">
  <figure>
    <img id="e-course" src="kurs-its.jpg" alt="exempel på e-kurs" />
    <figcaption>Kurs i LMS (itslearning)</figcaption>
  </figure>
</div>

<div class="e-course">
  <figure>
    <img id="e-course" src="teknisk-dok.jpg" alt="exempel på e-kurs" />
    <figcaption>Teknisk dokumentation</figcaption>
  </figure>
</div>

<div class="contact-button">
  <a id="contact" href="contact">
    <button id="send">Kontakta oss</button>
  </a>
</div>
