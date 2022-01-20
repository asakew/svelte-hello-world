<script>
  import Nested from './Nested.svelte';
  let siteName = 'app.uz';
	let src = '/tutorial/image.gif';
</script>

<h1>{siteName}</h1>

<img src={src}>

<p>This is a paragraph.</p>

<Nested />