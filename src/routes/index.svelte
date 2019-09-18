<style>
  @import url("https://fonts.googleapis.com/css?family=Overpass|Ruluko&display=swap");

  #logo {
    margin-left: 10px;
    margin-top: 40px;
  }

  h3 {
    margin-left: 12px;
    font-family: "Overpass", sans-serif;
    font-size: 1.2rem;
    font-weight: 300;
  }

  #small {
    width: 100%;
    max-width: 400px;
    margin: 0 0 1em 0;
  }

  .startImage-small {
    display: block
  }

  .startImage-big {
    visibility: hidden;
  }

  @media only screen and (min-width: 415px) {
    .page-container {
      background: url("");
      background-size: cover;
    }
    .startImage-small {
      display: none;
      z-index: -1;
    }
    .startImage-big {
    visibility: visible;
  }
    img {
    width: 100%;
    /* max-width: 400px; */
    margin: 0 0 1em 0;
  }
  }
</style>

<svelte:head>
  <title>learnweb</title>
</svelte:head>

<div class="page-container">
  <svg
    id="logo"
    xmlns="http://www.w3.org/2000/svg"
    xmlns:xlink="http://www.w3.org/1999/xlink"
    style="isolation:isolate"
    viewBox="230.5 136.75 183 55.47"
    width="169pt"
    height="55.47pt">
    <defs>
      <clipPath id="_clipPath_qAVaLgp9g35h5DwJHxwUtjy0breOmNEL">
        <rect x="230.5" y="136.75" width="183" height="55.47" />
      </clipPath>
    </defs>
    <g clip-path="url(#_clipPath_qAVaLgp9g35h5DwJHxwUtjy0breOmNEL)">
      <text
        transform="matrix(1,0,0,1,230.5,180.622)"
        style="font-family:'Ruluko';font-weight:400;font-size:48px;font-style:normal;fill:#4a4a55;stroke:none;">
        learnweb
      </text>
      <text
        transform="matrix(1,0,0,1,230.5,180.652)"
        style="font-family:'Ruluko';font-weight:400;font-size:48px;font-style:normal;fill:#4a4a55;stroke:none;">
        learnweb
      </text>
    </g>
  </svg>
  <h3>Uveckling av digitala lärresurser</h3>
  <div class="startImage-small">
    <img id="small" style="padding-top:3rem;" src="larresurs.png" alt="Lärresurs" />
  </div>
  <div class="startImage-big">
    <img width="800px" style="padding-top:3rem;" src="larresurs_big.jpg" alt="Lärresurs" />
  </div>
</div>
