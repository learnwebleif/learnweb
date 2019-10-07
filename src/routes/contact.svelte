<svelte:head>
	<title>Kontakt</title>
</svelte:head>
<script>
  import { onMount } from "svelte";
  import Modal from '../components/Modal.svelte';

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
form {
    margin: auto;
}
#form-header {
    display: block;
    margin-top: 0.8rem;
    margin-bottom: 3rem;
    width: 100%;
}
</style>

<form
  id="contact-form"
  action="https://getform.io/f/d1489453-2da8-4b4c-abea-3216b53852ee"
  method="POST">
  <div id="form-header">
    <p>Vi skulle bli jätteglada om du tog kontakt med oss. Fyll i dina uppgifter så hör vi av oss så fort vi kan.</p>
</div>
  <label>Namn:</label>
  <input type="text" name="name" />
  <label>E-post:</label>
  <input type="email" name="email" />
  <label>Meddelande:</label>
  <textarea name="comment" maxlength="500" form="contact-form"></textarea>
  <button id="send" type="submit">Skicka</button>
</form>
{#if showModal}
	<Modal on:close="{() => showModal = false}">
		<h2 slot="header">
			Skickat!
		</h2>

		<p>Tack för att du kontaktar oss. Vi kontaktar dig så snart vi kan.</p>
	</Modal>
{/if}