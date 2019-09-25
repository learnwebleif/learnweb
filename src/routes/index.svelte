<style>
  @import url("https://fonts.googleapis.com/css?family=Ubuntu&display=swap");

  #logo {
    margin-left: 10px;
    margin-top: 40px;
  }

  h2 {
    font-family: "Overpass", sans-serif;
    font-size: 1.5rem;
    font-weight: 500;
  }

  #small {
    width: 100%;
    max-width: 400px;
    margin: 0 0 1em 0;
  }

  .startImage-small {
    display: block;
  }

  .startImage-big {
    display: none;
  }

  @media only screen and (min-width: 415px) {
    .page-container {
      border: 0.6rem solid white;
      border-bottom: 0;
      background: url("");
      background-size: cover;
      background: #fafafa;
      padding: 0 4rem;
      border-radius: 8px;
    }
    .startImage-small {
      display: none;
      z-index: -1;
    }
    .startImage-big {
      display: block;
    }
    img {
      width: 100%;
      /* max-width: 400px; */
      margin: 0 0 1em 0;
    }
    #logo {
      margin-left: 0;
      margin-top: 40px;
    }
  }
  .service {
    background: white;
    display: flex;
    font-size: 0.8rem;
  }

  .frameworks {
    width: 50%;
    border: 0.6rem solid white;
    padding: 1.8em;
    padding: 1.8em;
    border-radius: 1rem;
    background: rgb(25, 164, 161);
    background: radial-gradient(
      circle,
      rgba(25, 164, 161, 1) 0%,
      rgba(25, 163, 160, 1) 57%,
      rgba(20, 147, 144, 1) 91%
    );
    color: #f8f8f8;
  }

  .lms {
    width: 50%;
    border: 0.6rem solid white;
    padding: 1.8em;
    padding-bottom: 1em;
    border-radius: 1rem;
    background: rgb(59, 162, 231);
    background: radial-gradient(
      circle,
      rgba(59, 162, 231, 1) 0%,
      rgba(56, 164, 235, 1) 47%,
      rgba(60, 157, 221, 1) 98%
    );
    color: #f8f8f8;
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
    viewBox="0 0 205 53.838"
    width="205pt"
    height="53.838pt">
    <defs>
      <clipPath id="_clipPath_0MDbOLkMMELSOJaGz2vTt8LnUrsXbtJY">
        <rect width="205" height="53.838" />
      </clipPath>
    </defs>
    <g clip-path="url(#_clipPath_0MDbOLkMMELSOJaGz2vTt8LnUrsXbtJY)">
      <text
        transform="matrix(1,0,0,1,0,44.736)"
        style="font-family:'Ubuntu';font-weight:400;font-size:48px;font-style:normal;fill:#4f4f4f;stroke:none;">
        learnweb
      </text>
      <text
        transform="matrix(1,0,0,1,0,44.766)"
        style="font-family:'Ubuntu';font-weight:400;font-size:48px;font-style:normal;fill:#4f4f4f;stroke:none;">
        learnweb
      </text>
    </g>
  </svg>
  <h2>Uveckling av digitala lärresurser</h2>
  <div class="startImage-small">
    <img
      id="small"
      style="padding-top:3rem;"
      src="larresurs.png"
      alt="Lärresurs" />
  </div>
  <div class="startImage-big">
    <img width="800px" src="larresurs_big.png" alt="Lärresurs" />
  </div>
</div>
<div class="service">
  <div class="frameworks">
    <h2>Webbdesign</h2>
    <p>
      Vår metod gör vi det möjligt för företag och utbildningsorganisationer
      att arbeta effektivt med kunskapshantering.
    </p>
    <button style="float:right;">Läs mer</button>
  </div>
  <div class="lms">
    <h2>System</h2>
    <p>
      Vi är experter på LMS och hur digitala lösningar kan skapa mervärde för både utbildare och studenter.
    </p>
    <button style="float: right;">Läs mer</button>
  </div>
</div>
