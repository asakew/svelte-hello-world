<script>
  import Nested from './Nested.svelte';
  let siteName = 'app.uz';
	let src = '/tutorial/image.gif';
	let string = `this string contains some <strong>HTML!!!</strong>`;
</script>

<h1>{siteName}</h1>

<img src={src}>

<p>This is a paragraph.</p>

<Nested />

<p>{string}</p>
