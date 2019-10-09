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
      max-width: 370px;
    }
    h1,
    h2 {
      font-family: "Quicksand", sans-serif;
    }
    p {
      font-family: "Quicksand", sans-serif;
    }
  }

  .framework {
    display: flex;
    justify-content: space-between;
    margin-top: 1rem;
    margin-bottom: 2rem;
  }
</style>

<svelte:head>
  <title>Webbutveckling</title>
</svelte:head>
<h1>Webbutveckling</h1>

<p>
  Det tog över 20 år innan det tekniken blev tillräckligt mogen för att skapa
  webbapplikationer (multimedia) om man räknar bort Adobe Flash. När Facebook
  för 6 år sedan lanserade React var det början på en utveckling som idag lett
  fram till flera fantastiska ramverk för att skapa webbapplikationer.
</p>

<p>
  Vi använder idag främst
  <a href="https://svelte.dev">Svelte</a>
  och
  <a href="https://vuejs.org/">Vue</a>
  kombinerat med
  <a href="https://bulma.io/">Bulma</a>
  eller
  <a href="https://tailwindcss.com/">tailwindcss.</a>
</p>

<div class="framework">
  <img width="75" height="23" src="svelte.png" alt="Svelte" />
  <img width="60" height="23" src="vue.png" alt="Vue" />
  <img width="65" height="23" src="bulma.png" alt="Bulma" />
  <img width="100" height="22" src="tailwind.png" alt="Tailwind" />
</div>

<h1>E-learning authoring tool</h1>

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

<h1>Vuepress</h1>

<p>
  För teknisk dokumentation använder vi Vuepress som är en "Vue-powered Static
  Site Generator". Vuepress använder Markdown och det går otroligt snabbt att
  utveckla innehåll utan att det innebär några begränsningar.
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
  <img src="responsiv.png" alt="Tillgänglighet" />
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

<!-- <p>
  Vi provar ständigt nya ramverk för att hitta de som fungerar bäst för våra
  projekt.
</p>

<p>
  Svelte är för tydlighetens skull inte ett ramverk utan en kompilator. Detta
  gör att prestandan blir oerhört bra men för vår del är kreativiteten och
  effektiviten avgörande i val av ramverk och verktyg.
</p> -->

<div style="margin-bottom: 3rem;">
  <p>
    <a href="https://multiple-choice.learnwebleif.now.sh/">Multiple choice</a>
    utvecklad i Svelte.
  </p>
  <div>
    <img src="mc.png" alt="Multiple choice" />
  </div>
</div>

<h2>E-kurser</h2>

<p>
  Vi har utvecklat hundratals e-kurser och digitala resureser genom åren med
  olika butgetar vilket gör att vi kan få ut det mesta av både stora och små
  projekt. Här är några exempel.
</p>

<div class="e-course">
  <figure>
    <img src="stom.png" alt="exempel på e-kurs" />
    <figcaption>Stöd- och matchningstjänst</figcaption>
  </figure>
</div>

<div class="e-course">
  <figure>
    <img src="lmsecourse.png" alt="exempel på e-kurs" />
    <figcaption>Kurs i LMS (itslearning)</figcaption>
  </figure>
</div>

<div class="e-course">
  <figure>
    <img src="tekniskdok.png" alt="exempel på e-kurs" />
    <figcaption>Teknisk dokumentation</figcaption>
  </figure>
</div>

<div class="contact-button">
  <a href="contact">
    <button id="send">Kontakta oss</button>
  </a>
</div>
