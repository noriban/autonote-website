<script>
    import logo from '../assets/logo.svg'
    // import '../styles/button.css'
</script>
<nav class="bg-gray-200 shadow shadow-gray-300 w-100 sm:py-4 md:px-0 md:py-0 md:w-4/5 lg:w-3/4 md:mx-auto md:rounded-full md:my-3 xl:w-1/2">
	<div class="md:h-16 h-28 mx-auto md:pl-4 md:pr-0 container flex items-center justify-between flex-wrap md:flex-nowrap ">
		<!-- Logo -->
		<div class="mx-3 md:mx-0 md:order-1">
			<!-- Heroicon - Chip Outline -->
      <a href="/">
        <img class="h-16 w-16 flex-1 md:rounded-full" src="{logo}" alt="logo">
      </a>
		</div>
		<div class="text-gray-500 order-3 w-full md:w-auto md:order-2">
			<ul class="flex font-semibold justify-evenly lg:justify-between">
                <!-- Active Link = text-indigo-500
                Inactive Link = hover:text-indigo-500 -->
				<li class="nav_item"><a href="#features">Features</a></li>
				<li class="nav_item"><a href="#about">FAQ</a></li>
				<li class="nav_item"><a href="/roadmap">Roadmap</a></li>
				<li class="nav_item"><a href="https://github.com/noriban/AutoNote">Source</a></li>
			</ul>
		</div>
		<div class="order-2 md:order-3">
      <a href="https://github.com/noriban/AutoNote/releases">
        <button class="downButton mx-3 px-3 py-4 sm:px-2 shadow-2xl bg-indigo-500 hover:bg-indigo-700 text-gray-50 rounded-3xl flex items-center gap-2 md:py-3">
        <!-- Heroicons - Login Solid -->
        <span class="mx-3">Download</span>
      </button>
      </a>
		</div>
	</div>
</nav>