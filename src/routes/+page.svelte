<h1>Hello, I'm Jacqueline 👋🏽</h1>
<h2>Feel free to play around with my Svelte app</h2>
<h3>I'm still learning Svelte so this is my playground 👩🏽‍💻</h3>

<script>
	let a = 1;
	let b = 2;
  let name = "";


</script>

<form>
  <input placeholder="Enter your name" type="string" bind:value={name}>
<input type="number" bind:value={a}>
<input type="number" bind:value={b}>
</form>

<p>{name} the sum is {a + b}</p>

<style>
	:global(body) {
		padding: 20px 30px;
		margin: 0;
    background: #dddddd;
    color: #870000;
    font-size: 20px;
	}

  input {
    padding: 10px;
    margin-right: 5px;
    border-radius: 8px;
    border: 1px solid #870000;
  }

  :global(button) {
    padding:10px 15px;
    margin: 0 5px 0 0;
    border-radius: 8px;
    background: #fff;
    border: 1px solid #870000;
    box-shadow: 2px 2px 3px #000;
  }

  :global(button:hover) {
    background: #870000;
    color: #fff;
    cursor: pointer;
  }
	
</style>