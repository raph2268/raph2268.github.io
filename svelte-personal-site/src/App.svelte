<script>
	export let name;
  
	function toggleName() {
	  if (name === "world") {
		name = "Svelte";
	  } else {
		name = "Raphael";
	  }
	}
  </script>
  
  <main>
	<h1>Hi {name}!</h1>
	<button on:click="{toggleName}">Toggle name</button>
	<p>
	  Visit the <a href="https://learn.svelte.dev/">Svelte tutorial</a> to learn
	  how to build Svelte apps.
	</p>
  </main>
  