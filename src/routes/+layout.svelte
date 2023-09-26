<script lang="ts">
	import '../app.css';
</script>

<main>
	<slot/>
</main>

<footer>
	
</footer>

<style>
	@import url("../app.css");
	:root {
		font-family: var(--fds-font-family-display);
		background-size: cover;
		font-size: 16px;
		text-align: left;
		background-image: var(--fds-mica-background-base), var(--bg);
	}
	@media(prefers-color-scheme: light){
		:root{
			color: black;
			--bg: url("https://cdn.wallpaperhub.app/cloudcache/8/e/c/4/4/f/8ec44f86876a912a93f4116f50e6a3839af5c03b.jpg");
		}
	}
	@media(prefers-color-scheme: dark){
		:root{
			color: white;
			--bg: url("https://cdn.wallpaperhub.app/cloudcache/a/1/c/a/d/b/a1cadb0911675232054cc13deee6a3221b4dd88e.jpg");
		}
	}
	::-webkit-scrollbar {
		width: 8px;
	}
	::-webkit-scrollbar-track {
		background: transparent; 
	}
	::-webkit-scrollbar-thumb {
	  	background: #555;
	  	border-radius: 10px;
	  	padding: 2px;
	}
	::-webkit-scrollbar-thumb:hover {
	  	background: #888;
	}
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		margin: 0 auto;
		box-sizing: border-box;
	}
	
	footer {
		display: flex;
		flex-direction: column;
		justify-content: stretch;
		align-items: stretch;
		padding: 40px;
	}
	@media (min-width: 480px) {
		footer {
			padding: 0px 40px 40px;
		}
	}
</style>