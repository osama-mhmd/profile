<script>
	import { MapPin, Link, Flame, Calendar, Moon, Folder } from "lucide-svelte";
</script>

<section class="mt-12">
	<div class="container">
		<h1>Osama Mohammed</h1>
		<p class="have-icon"><MapPin /> Egypt, Full Stack Developer</p>
	</div>
</section>

<section>
	<div class="container">
		<h2 class="mb-2 have-icon">Projects <Folder /></h2>
		<div class="rounded-md border border-blue-600 bg-blue-100 p-4">
			<h3>
				<a class="have-icon" href="https://nonote.vercel.app/" target="_blank"
					>Nonote <Link size={20} /></a
				>
			</h3>
			<div class="mt-2">
				Free, <span class="highlighted">Open Source</span>, and for developers note taking app.
				<ul>
					<li>With the support of workspaces (public, private).</li>
					<li>
						<span class="have-icon"
							><Flame fill="#fbbf24" /> The editor is built on top of Tiptap</span
						>
					</li>
					<li><span class="have-icon"><Calendar /> Habit tracker</span></li>
					<li><span class="have-icon"><Moon /> Muslim Notebook</span></li>
				</ul>
			</div>
			<p class="mt-4 mb-2">
				<span class="tag">Typescript</span>
				<span class="tag">nextjs</span>
				<span class="tag">postgres</span>
				<span class="tag">lucia</span>
				<span class="tag">Drizzle ORM</span>
				<span class="tag">tiptap</span>
			</p>
		</div>
	</div>
</section>
