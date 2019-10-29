<style>
  @import url("https://fonts.googleapis.com/css?family=Quicksand|Ubuntu&display=swap");
  img {
    display: flex;
    margin-top: 3rem;
    margin-bottom: 5rem;
    width: 50%;
  }
  .accesibility-2 {
    width: 100% !important;
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

  @media (min-width: 40rem) {
    figcaption {
      margin-top: 1rem;
    }
    img {
      display: block;
      margin-top: 4rem;
      margin-bottom: 5rem;
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
    .multiple-choice {
      width: 80%;
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
  När Facebook för 6 år sedan lanserade React var det början på en utveckling
  som idag lett fram till flera fantastiska ramverk för att skapa
  webbapplikationer. En arkitektur som vi har anammat är
  <a href="https://jamstack.org/">JAMstack</a>
  och vi använder idag främst
  <a href="https://svelte.dev">Svelte</a>
  och
  <a href="https://vuejs.org/">Vue</a>
  kombinerat med
  <a href="https://bulma.io/">Bulma</a>
  eller
  <a href="https://tailwindcss.com/">tailwindcss.</a>
</p>

<div class="framework">
  <!-- <img width="75" height="23" src="svelte.png" alt="Svelte" /> -->
  <img id="svelte-img" src="svelte.png" alt="Svelte" />
  <!-- <img width="60" height="23" src="vue.png" alt="Vue" /> -->
  <img id="vue-img" src="vue.png" alt="Vue" />
  <!-- <img width="65" height="23" src="bulma.png" alt="Bulma" /> -->
  <img id="bulma-img" src="bulma.png" alt="Bulma" />
  <!-- <img width="100" height="22" src="tailwind.png" alt="Tailwind" /> -->
  <img id="tailwind-img" src="tailwind.png" alt="Tailwind" />
</div>

<h1>E-learning</h1>

<p>
  För traditionell e-learning använder vi
  <a href="https://www.adaptlearning.org/">Adapt</a>
  . Med Adapt får man SCORM-funktionalitet vilket gör att man kan kommunicera
  med ett LMS för att spara t.ex. progression eller resultat från ett test etc.
</p>
<p>
  <a href="pedagogy">Läs mer</a>
  om SCORM och LMS.
</p>

<div class="adapt">
  <img src="adapt.png" alt="adapt" />
</div>

<h1>Teknisk dokumentation</h1>

<p>
  För teknisk dokumentation använder vi Vuepress som är en "Vue-powered Static
  Site Generator". Vuepress använder Markdown för att skapa huvuddelen av
  innehållet vilket gör det oerhört enkelt och kostnadseffektivt producera
  innehåll men det finns även en möjlighet att använda Vue för mer avancerade
  funktioner.
</p>

<div class="vuepress">
  <img src="vuepress.png" alt="Vuepress" />
</div>

<h1>Tillgänglighet</h1>

<p>
  För att göra innehållet tillgängligt för så många som möjligt försöker vi
  arbeta med semantisk html, talsyntes, responsiv design samt optimerar
  innehållet för långsamma nätverk.
</p>

<div class="accesibility-1">
  <img src="talsyntes.png" alt="Tillgänglighet" />
</div>
<div class="accesibility-2">
  <img style="width: 300px;" src="responsiv.png" alt="Tillgänglighet" />
</div>

<div style="margin-bottom: 7rem;">
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
</div>

<h1>Exempelprojekt</h1>

<div style="margin-bottom: 3rem;">
  <p>Multiple choice utvecklad i Svelte.</p>
  <div class="contact-button">
    <a href="https://multiple-choice.learnwebleif.now.sh/">
      <button id="send">Demo</button>
    </a>
  </div>
  <div class="multiple-choice">
    <img src="mc.png" alt="Multiple choice" />
  </div>
</div>

<h2>E-kurser</h2>

<p>
  Vi har utvecklat hundratals e-kurser och digitala resureser genom åren med
  olika budgetar vilket gör att vi kan få ut det mesta av både stora och små
  projekt. Här är några exempel.
</p>

<div class="e-course">
  <figure>
    <img src="stom-ex.png" alt="exempel på e-kurs" />
    <figcaption>Stöd- och matchningstjänst</figcaption>
  </figure>
</div>

<div class="e-course">
  <figure>
    <img src="kurs-its.jpg" alt="exempel på e-kurs" />
    <figcaption>Kurs i LMS (itslearning)</figcaption>
  </figure>
</div>

<div class="e-course">
  <figure>
    <img src="teknisk-dok.jpg" alt="exempel på e-kurs" />
    <figcaption>Teknisk dokumentation</figcaption>
  </figure>
</div>

<div class="contact-button">
  <a href="contact">
    <button id="send">Kontakta oss</button>
  </a>
</div>
