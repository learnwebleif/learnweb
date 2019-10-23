<script>
  import { onMount } from "svelte";
  import Modal from "../components/Modal.svelte";

  let showModal = false;

  onMount(() => {
    const formElement = document.querySelector("#contact-form");
    formElement.addEventListener("submit", event => {
      event.preventDefault();
      const data = new URLSearchParams(new FormData(formElement));
      fetch("https://getform.io/f/d1489453-2da8-4b4c-abea-3216b53852ee", {
        method: "post",
        body: data
      });
      showModal = true;
    });
  });
</script>

<style>
  @import url("https://fonts.googleapis.com/css?family=Quicksand&display=swap");
  @media (min-width: 40rem) {
    #form-header {
      font-family: "Quicksand", sans-serif;
    }

    h1 {
      font-size: 2rem;
    }
    #form-header > p {
      color: #69778b;
    }
    form {
      -webkit-font-smoothing: antialiased;
      padding: 10px 18px 20px 24px;
    }
    .contact-form {
      box-sizing: border-box;
      border-radius: 4px;
      box-shadow: 0 50px 100px -20px rgba(50, 50, 93, 0.25),
        0 30px 60px -30px rgba(0, 0, 0, 0.3),
        0 -18px 60px -10px rgba(0, 0, 0, 0.025);
      max-width: 545px;
      background: #fff;
    }
    #form-header {
      display: block;
      margin-top: 0.8rem;
      margin-bottom: 3rem;
      width: 100%;
    }
    .form-row {
      display: flex;
    }
    .form-row > label {
      -webkit-font-smoothing: antialiased;
      text-rendering: optimizeLegibility;
      box-sizing: border-box;
      -webkit-tap-highlight-color: transparent;
      display: block;
      color: #424770;
      font-size: 15px;
      font-weight: 500;
      letter-spacing: normal;
      line-height: 26px;
      margin-right: 20px;
      align-self: center;
      flex: 32%;
    }
    .clearfix::after {
      content: "";
      clear: both;
      display: table;
    }
    input,
    textarea {
      display: block;
      border: none;
      outline: none;
      border-radius: 4px;
      color: #32325d;
      font-weight: 400;
      font-size: 15px;
      background-color: #f6f9fc;
      padding: 5px 20px 8px 13px;
      flex: 68%;
    }
  }
</style>

<svelte:head>
  <title>Kontakt</title>
</svelte:head>

<div id="form-header">
  <h1>Skriv till oss</h1>
  <p>Vi återkopplar snarast möjligt.</p>
</div>
<div class="contact-form">
  <form
    id="contact-form"
    action="https://getform.io/f/d1489453-2da8-4b4c-abea-3216b53852ee"
    method="POST">

    <div class="form-row">
      <label class="first-name">Namn</label>
      <input type="text" name="name" />
    </div>
    <div class="form-row">
      <label class="email">E-post</label>
      <input type="email" name="email" placeholder="@" />
    </div>
    <div class="form-row">
      <label style="align-self: flex-start; padding-top: 12px;">
        Meddelande
      </label>
      <textarea
        name="comment"
        maxlength="500"
        form="contact-form" />
    </div>
    <div style="float: right;">
      <button id="send" type="submit">Skicka</button>
    </div>
    <div class="clearfix" />
  </form>
</div>
{#if showModal}
  <Modal on:close={() => (showModal = false)}>
    <h2 slot="header">Skickat!</h2>

    <p>Tack för att du kontaktar oss. Vi kontaktar dig så snart vi kan.</p>
  </Modal>
{/if}
