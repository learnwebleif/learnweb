<script>

import {onMount} from 'svelte';

onMount(() => {
    const formElement = document.querySelector('#contact-form');
    formElement.addEventListener('submit', (event) => {
        event.preventDefault();
        const data = new URLSearchParams(new FormData(formElement));
        fetch('https://getform.io/f/d1489453-2da8-4b4c-abea-3216b53852ee', {
            method: 'post',
            body: data
        });
        alert('Thank you for submitting')
    })
})

</script>

<h1>Pedagogik</h1>

<h2>Learning Management Systems</h2>

<p>
  Ett bra innehåll och en tydlig struktur är alltid grunden för ett lyckat
  genomförande av en utbildning. Vi har lång erfarenhet av samarbeten med
  pedagoger och ämnesexperter. Alla LMS, LSX och andra lärsystem är
  webbapplikationer och eftersom vi är webbutvecklare är det vår hemmaplan. Vi
  kan garantera att er organisation kan få ut maximalt av en digital satsning
  oavsett om det handlar om utveckling av digitalt innehåll, utbildning eller
  support.
</p>

<!-- <img width="100%" src="lms.png" alt="LMS" /> -->
<div
  style="display: flex; justify-content: center; margin-top: 3rem;
  margin-bottom: 5rem;">
  <img width="80%" src="lms.png" alt="LMS" />
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

<div
  style="display: flex; justify-content: center; margin-top: 3rem;
  margin-bottom: 4rem;">
  <img width="255px" src="vuepress.png" alt="Vuepress" />
</div>

<h1>Kurs i webbpedagogik</h1>

<p>
  Vi vill gärna erbjuda pedagoger och ämnesexperter utbildning i webbutveckling
  och mediaproduktion för webben. Vi har ett färdigt upplägg som kan anpassas efter
  individuella önskemål.
</p>

<div
  style="display: flex; justify-content: center; margin-top: 3rem;
  margin-bottom: 4rem;">
</div>

<a href="contact"><button id="send">Kontakt</button></a> <a href="webdesign"><button id="send">webbutveckling</button></a>