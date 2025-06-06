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
				Someone learning C#, C++, Java, HTML, and Python. Always open to
				friendly DMs.<br />
				I'm passionate about computers, programming, maths, and music. I
				like physics and chemistry too. Fiddling with desktop and mobile
				OSes was a considerable chunk of my life in 2020 and 2021.<br />
				I'm somewhat of a musician, although I don't make music. I play the
				keyboards, and have a Yamaha PSR-I455 for the purpose. Taking a music
				break really helps when it comes to any task, and that's why I love
				music.
				<br /><br />
				I'm usually active on Discord when it comes to development. Feel
				free to join the Developer Sanctuary Discord server and check out
				the #donut-projects channel, if you want to see what I'm working
				on next!<br /><br />
				<Fluent.Button
					variant="hyperlink"
					href="https://discord.gg/windows-apps-hub-714581497222398064"
					target="_blank"
					rel="noopener noreferrer"
					>Invite link (permanently valid)</Fluent.Button
				>
			</Fluent.TextBlock>
		</div>
	</div>
	<div class="card">
		<h2 class="pad bgs">GitHub statistics</h2>
		<div class="pad">
			<table>
				<tr>
					<td>
						<img src="https://github-readme-stats.vercel.app/api?username=donut2008&show_icons=true&theme=dark"
						alt="GitHub stats"
						style="width: auto !important; height: auto !important;"/>
					</td>
					<td>
						<img src="https://github-readme-streak-stats.herokuapp.com?user=donut2008&theme=dark"
						alt="GitHub Streak"
						style="width: auto !important; height: auto !important;"/>
					</td>
					<td>
						<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=donut2008&theme=dark"
						alt="Most used languages"
						style="width: auto !important; height: auto !important;"/></td>
				</tr>
			</table>
		</div>
	</div>
	<div class="card">
		<h2 class="pad bgs">Kernels</h2>
		<div class="pad">
			<Fluent.Button
				style="margin: 2px 0;"
				variant="standard"
				href="https://github.com/donut2008/kernel_samsung_universal7904"
				target="_blank"
				rel="noopener noreferrer"
			>
				<figure style="margin: 0;">
					<img
						src="https://raw.githubusercontent.com/donut2008/donut2008.vercel.app/master/img/A30s.png"
						alt="Samsung Galaxy A30s"
						style="width: 128px !important; height: 128px !important;"
					/>
					<figcaption class="ctext">
						<Fluent.TextBlock>Samsung Galaxy A30s (universal7904, 4.4.177)</Fluent.TextBlock>
					</figcaption>
				</figure>
			</Fluent.Button>
			<Fluent.Button
				style="margin: 2px 0;"
				variant="standard"
				href="https://github.com/donut2008/kernel_samsung_sm6150"
				target="_blank"
				rel="noopener noreferrer"
			>
				<figure style="margin: 0;">
					<img
						src="https://raw.githubusercontent.com/donut2008/donut2008.vercel.app/master/img/M40.png"
						alt="Samsung Galaxy M40"
						style="width: 128px !important; height: 128px !important;"
					/>
					<figcaption class="ctext">
						<Fluent.TextBlock>Samsung Galaxy M40 (sm6150, 4.14.190)</Fluent.TextBlock>
					</figcaption>
				</figure>
			</Fluent.Button>
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
							href="Calculator"
							target="_blank"
							rel="noopener noreferrer">Calculator</Fluent.Button
						>
					</li>
					<li>
						<Fluent.Button
							variant="hyperlink"
							href="https://neonx.vercel.app"
							target="_blank"
							rel="noopener noreferrer">NeonX</Fluent.Button
						>
					</li>
					<li>
						<Fluent.Button
							variant="hyperlink"
							href="UWPDrawingCanvas"
							target="_blank"
							rel="noopener noreferrer"
							>Drawing Canvas UWP</Fluent.Button
						>
					</li>
					<li>
						<Fluent.Button
							variant="hyperlink"
							href="DonutOS"
							target="_blank"
							rel="noopener noreferrer">DonutOS</Fluent.Button
						>
					</li>
					<li>
						<Fluent.Button
							variant="hyperlink"
							href="WinTranslate"
							target="_blank"
							rel="noopener noreferrer"
							>WinTranslate</Fluent.Button
						>
					</li>
					<li>
						<Fluent.Button
							variant="hyperlink"
							href="DeleteInverter"
							target="_blank"
							rel="noopener noreferrer"
							>DeleteInverter</Fluent.Button
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
				style="margin: 2px 0;"
				variant="standard"
				href="https://telegram.me/donut6150"
				target="_blank"
				rel="noopener noreferrer"
			>
				<figure style="margin: 0;">
					<img
						src="https://raw.githubusercontent.com/donut2008/donut2008.vercel.app/master/img/telegram.svg"
						alt="Telegram"
					/>
					<figcaption class="ctext">
						<Fluent.TextBlock>donut6150</Fluent.TextBlock>
					</figcaption>
				</figure>
			</Fluent.Button>
			<Fluent.Button
				style="margin: 2px 0;"
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
				style="margin: 2px 0;"
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
				style="margin: 2px 0;"
				variant="standard"
				href="https://youtube.com/@WalnutException"
				target="_blank"
				rel="noopener noreferrer"
			>
				<figure style="margin: 0;">
					<img
						src="https://raw.githubusercontent.com/donut2008/donut2008.vercel.app/master/img/youtube.svg"
						alt="YouTube"
					/>
					<figcaption class="ctext">
						<Fluent.TextBlock>@WalnutException</Fluent.TextBlock>
					</figcaption>
				</figure>
			</Fluent.Button>
			<Fluent.Button
				style="margin: 2px 0;"
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
