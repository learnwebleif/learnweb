<script>
  import { createEventDispatcher } from "svelte";

  const dispatch = createEventDispatcher();
</script>

<style>
  .modal-background {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.3);
  }

  .modal {
    position: absolute;
    left: 50%;
    top: 50%;
    width: calc(100vw - 4em);
    max-width: 32em;
    max-height: calc(100vh - 4em);
    overflow: auto;
    transform: translate(-50%, -50%);
    padding: 1em;
    border-radius: 0.2em;
    background: white;
  }

  button {
    display: block;
    -webkit-box-direction: normal;
    -webkit-font-smoothing: antialiased;
    font-feature-settings: "pnum";
    box-sizing: border-box;
    -webkit-tap-highlight-color: transparent;
    white-space: nowrap;
    display: inline-block;
    height: 40px;
    line-height: 40px;
    padding: 0 14px;
    box-shadow: 0 4px 6px rgba(50, 50, 93, 0.11), 0 1px 3px rgba(0, 0, 0, 0.08);
    border-radius: 4px;
    font-size: 15px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.025em;
    text-decoration: none;
    transition: all 0.15s ease;
    color: #fff;
    background: #6772e5;
    -webkit-appearance: none;
    outline: none;
    border: none;
    cursor: pointer;
    font-family: inherit;
  }
</style>

<div class="modal-background" on:click={() => dispatch('close')} />

<div class="modal">
  <slot name="header" />
  <hr />
  <slot />
  <hr />

  <button on:click={() => dispatch('close')}>Stäng</button>
</div>
