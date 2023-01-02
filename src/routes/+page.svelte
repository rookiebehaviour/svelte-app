<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<form method="POST" action="?/login">
  <label>
    Email
    <input name="email" type="email" autocomplete="off">
  </label>
  <label>
    Password
    <input name="password" type="password">
  </label>
  <button>Log in</button>
	<button formaction="?/register">Register</button>
</form>