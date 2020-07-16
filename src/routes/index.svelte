<style>
  @import url("https://fonts.googleapis.com/css?family=Quicksand|Ubuntu&display=swap");
  @import url("https://fonts.googleapis.com/css?family=Montserrat&display=swap");

  #logo {
    margin-left: 0;
    margin-top: 40px;
  }

  h2 {
    font-size: 1.2rem;
    font-weight: 500;
    color: #4f4f4f;
  }

  #hi {
    font-family: "Quicksand", sans-serif;
    font-size: 2rem;
    font-weight: 500;
    color: #4f4f4f;
    padding-top: 5rem;
  }

  #logo-text {
    font-family: "Quicksand", sans-serif;
    font-size: 1.2rem;
    font-weight: 500;
    color: #4f4f4f;
    padding-bottom: 5rem;
  }

  #startpage-text {
    font-family: "Montserrat", sans-serif;
    font-variant-numeric: proportional-nums;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-weight: 400;
    font-size: 18px;
    line-height: 32px;
    color: #495572;
    padding: 2rem 1rem;
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

  .service {
    background: white;
    font-size: 1rem;
  }

  .service h2 {
    color: white;
  }

  .frameworks {
    border: 0.6rem solid white;
    padding: 1.8em;
    padding-bottom: 2.5rem;
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
    border: 0.6rem solid white;
    padding: 1.8em;
    padding-bottom: 2.5rem;
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

  @media only screen and (min-width: 415px) {
    .service {
      background: white;
      display: flex;
      font-size: 0.8rem;
    }

    .service h2 {
      color: white;
    }

    .frameworks {
      width: 50%;
      border: 0.6rem solid white;
      padding: 1.8em;
      padding-bottom: 2.5rem;
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
      padding-bottom: 2.5rem;
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
      margin: 0 0 1em 0;
    }
  }

  a:after {
    padding-left: 0.5rem;
    content: url("arrow.svg");
  }

  .learn-more {
    -webkit-box-direction: normal;
    font-style: normal;
    -webkit-font-smoothing: antialiased;
    text-rendering: optimizeLegibility;
    box-sizing: border-box;
    text-decoration: none;
    outline: none;
    font-size: 17px;
    font-weight: 500;
    cursor: pointer;
  }
</style>

<svelte:head>
  <title>learnweb</title>
</svelte:head>

<div class="page-container">
  <!-- <svg
    id="logo"
    xmlns="http://www.w3.org/2000/svg"
    xmlns:xlink="http://www.w3.org/1999/xlink"
    style="isolation:isolate"
    viewBox="0 0 205 53.838"
    width="180pt"
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
  </svg> -->
  <h1 id="hi">Hi!</h1>
  <h2 id="logo-text">We are currently working on a new project. Welcome back in the future...</h2>
  
  <!-- <div class="startImage-small">
    <img
      id="small"
      style="padding-top:3rem;"
      src="larresurs.png"
      alt="Lärresurs" />
  </div> -->
  <!-- <div class="startImage-big">
    <img width="800px" src="larresurs_big.png" alt="Lärresurs" />
  </div> -->
</div>
<!-- <div id="startpage-text">
  <p>
    Genom att använda moderna ramverk för webbutveckling skapar learnweb
    tillsammans med pedagoger framtidens digitala resurser.
  </p>
</div> -->
<!-- <div class="service">
  <div class="frameworks">
    <h2>Webbutveckling</h2>
    <p>
      Vi fokuserar på tekniken så att pedagoger kan fokusera på innehållet.
      Tillsammans skapar det en kreativ miljö för utvecklare och pedagoger.
    </p>
    <br />
    <a class="learn-more" style="float: right;" href="webdesign">Läs mer</a>
  </div>
  <div class="lms">
    <h2>Pedagogik</h2>
    <p>
      Vi är experter på lärsystem och hur digital pedagogisk utveckling kan
      skapa mervärde för utbildare och studenter.
    </p>
    <br />
    <a class="learn-more" style="float: right;" href="pedagogy">Läs mer</a>
  </div>
</div> -->
