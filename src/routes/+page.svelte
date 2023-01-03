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
  <button>Save</button>
<input type="number" bind:value={a}>
<input type="number" bind:value={b}>
</form>

<p>{a} + {b} = {a + b} 
  <br/>
<br/>
  Hello {name}</p>

<style>
	:global(body) {
		/* this will apply to <body> */
      padding: 20px 30px;
		margin: 0;
    background: #dddddd;
    color: #870000;
    font-size: 20px;
	}

  input {
    padding: 10px;
    margin-right: 10px;
    border-radius: 8px;
    border: 2px solid #870000;
  }

  button {
    padding:10px 15px;
    border-radius: 8px;
    background: #fff;
    border: none;
    box-shadow: 2px 2px 3px black;
  }

  button:hover {
    background: #870000;
    color: #fff;
    
  }
	
</style>