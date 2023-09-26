<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
</script>

<div class="main">
	<h1 class="ctext">donut2008</h1>
	<div class="pad ctext">
		<Fluent.TextBlock>Welcome to donut2008's homepage!</Fluent.TextBlock>
	</div>
	<div class="card">
		<h2 class="pad bgs">About me</h2>
		<div class="pad">
			<Fluent.TextBlock>
				Some guy learning C#, C++, Java, HTML, and CSS. Always open to
				friendly DMs.<br />
				I'm passionate about computers, programming, maths, and music. I
				like physics and chemistry too. Fiddling with desktop and mobile
				OSes was a considerable chunk of my life in 2020 and 2021.<br />
				I'm somewhat of a musician, although I don't make music. I play the
				keyboards, and have a Yamaha PSR-I455 for the purpose. Taking a music
				break really helps when it comes to any task, and that's why I love
				music.
			</Fluent.TextBlock>
		</div>
	</div>
	<div class="card">
		<h2 class="pad bgs">GitHub projects</h2>
		<div class="pad">
			<Fluent.TextBlock>
				<ul>
					<li>
						<Fluent.Button
							variant="hyperlink"
							href="https://donut2008.github.io/Calculator"
							target="_blank"
							rel="noopener noreferrer">Calculator</Fluent.Button
						>
					</li>
					<li>
						<Fluent.Button
							variant="hyperlink"
							href="https://donut2008.github.io/NeonX"
							target="_blank"
							rel="noopener noreferrer">NeonX</Fluent.Button
						>
					</li>
					<li>
						<Fluent.Button
							variant="hyperlink"
							href="https://donut2008.github.io/UWPDrawingCanvas"
							target="_blank"
							rel="noopener noreferrer"
							>Drawing Canvas UWP</Fluent.Button
						>
					</li>
					<li>
						<Fluent.Button
							variant="hyperlink"
							href="https://donut2008.github.io/DonutOS"
							target="_blank"
							rel="noopener noreferrer">DonutOS</Fluent.Button
						>
					</li>
					<li>
						<Fluent.Button
							variant="hyperlink"
							href="https://donut2008.github.io/WinTranslate"
							target="_blank"
							rel="noopener noreferrer"
							>WinTranslate</Fluent.Button
						>
					</li>
				</ul>
			</Fluent.TextBlock>
		</div>
	</div>
	<div class="card">
		<h2 class="pad bgs">Socials</h2>
		<div class="pad">
			<Fluent.Button
				variant="standard"
				href="https://telegram.me/donut2008"
				target="_blank"
				rel="noopener noreferrer"
			>
				<figure style="margin: 0;">
					<img
						src="https://raw.githubusercontent.com/donut2008/donut2008.vercel.app/master/img/telegram.svg"
						alt="Telegram"
					/>
					<figcaption class="ctext">
						<Fluent.TextBlock>donut2008</Fluent.TextBlock>
					</figcaption>
				</figure>
			</Fluent.Button>
			<Fluent.Button
				variant="standard"
				href="https://discord.com/users/796351855181037569"
				target="_blank"
				rel="noopener noreferrer"
			>
				<figure style="margin: 0;">
					<img
						src="https://raw.githubusercontent.com/donut2008/donut2008.vercel.app/master/img/discord.svg"
						alt="Discord"
					/>
					<figcaption class="ctext">
						<Fluent.TextBlock>donut2008</Fluent.TextBlock>
					</figcaption>
				</figure>
			</Fluent.Button>
			<Fluent.Button
				variant="standard"
				href="https://github.com/donut2008"
				target="_blank"
				rel="noopener noreferrer"
			>
				<figure style="margin: 0;">
					<img
						src="https://raw.githubusercontent.com/donut2008/donut2008.vercel.app/master/img/github.svg"
						alt="Github"
					/>
					<figcaption class="ctext">
						<Fluent.TextBlock>donut2008</Fluent.TextBlock>
					</figcaption>
				</figure>
			</Fluent.Button>
			<Fluent.Button
				variant="standard"
				href="https://youtube.com/@donut2008"
				target="_blank"
				rel="noopener noreferrer"
			>
				<figure style="margin: 0;">
					<img
						src="https://raw.githubusercontent.com/donut2008/donut2008.vercel.app/master/img/youtube.svg"
						alt="YouTube"
					/>
					<figcaption class="ctext">
						<Fluent.TextBlock>@donut2008</Fluent.TextBlock>
					</figcaption>
				</figure>
			</Fluent.Button>
			<Fluent.Button
				variant="standard"
				href="http://live.xbox.com/Profile?Gamertag=FireFox44039"
				target="_blank"
				rel="noopener noreferrer"
			>
				<figure style="margin: 0;">
					<img
						src="https://raw.githubusercontent.com/donut2008/donut2008.vercel.app/master/img/xbox.svg"
						alt="Xbox"
					/>
					<figcaption class="ctext">
						<Fluent.TextBlock>FireFox44039</Fluent.TextBlock>
					</figcaption>
				</figure>
			</Fluent.Button>
		</div>
	</div>
</div>
<footer class="fb">
	<Fluent.TextBlock>© donut2008 2021-present.</Fluent.TextBlock>
</footer>

<style>
	@import url("../app.css");
	:root {
		font-family: var(--fds-font-family-display);
		background-size: cover;
		font-size: 16px;
		text-align: left;
		background-image: var(--fds-mica-background-base), var(--bg);
		color-scheme: var(--cs);
	}
	@media (prefers-color-scheme: light) {
		:root {
			color: black;
			--bg: url("https://cdn.wallpaperhub.app/cloudcache/8/e/c/4/4/f/8ec44f86876a912a93f4116f50e6a3839af5c03b.jpg");
			--cs: light;
		}
	}
	@media (prefers-color-scheme: dark) {
		:root {
			color: white;
			--bg: url("https://cdn.wallpaperhub.app/cloudcache/a/1/c/a/d/b/a1cadb0911675232054cc13deee6a3221b4dd88e.jpg");
			--cs: dark;
		}
	}
	.main {
		margin: 0;
		overflow: overlay;
		width: 100%;
		height: 100%;
	}
	.fb {
		background: var(--fds-smoke-background-default);
		bottom: 0;
		left: 0;
		position: fixed;
		padding: 4px;
		display: flex;
		flex: 1;
		justify-content: center;
		align-items: center;
	}
	.pad {
		padding: 16px;
	}
	.ctext {
		text-align: center;
	}
	h1 {
		font-size: 40px;
	}
	.card {
		border-radius: 8px;
		background: var(--fds-card-background-default);
		box-shadow: var(--fds-card-shadow);
		border: var(--fds-control-border-default);
	}
	.bgs {
		background: var(--fds-card-background-secondary);
		border-radius: 8px 8px 0 0;
	}
	img {
		display: block;
		margin-left: auto;
		margin-right: auto;
		width: 32px;
		height: 32px;
		padding: 8px 32px;
	}
</style>
