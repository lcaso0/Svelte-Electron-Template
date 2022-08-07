<!-- 
	1. npx degit sveltejs/template project-name
	2. npm install --save-dev electron
	3. add "start": "electron ." to package.json scripts
	4. add "main": "./electron/index.js", to package.json
	5. put ./ on index.html file
	6. npm run dev
	7. add bundle.css on public build
	8. make electron folder
	9. npm run dev or npm run start   to run project
-->

<script>
	var count = 0;
</script>

<main>
	<h1>{count}</h1>
	<button on:click={() => count++}>Increase</button>
</main>