<script>
    import "../app.css";
  </script>

<nav class='container flex justify-between mx-auto w-full text-4xl font-semibold p-4 bg-muted/40'>
    <a>Home</a>
    <a>Search</a>
    <a>Login</a>
</nav>

<main class="flex flex-grow justify-center bg-muted/40 ">
	<div class="container p-5">
		<slot />
	</div>
</main>

<footer class="flex justify-center bg-muted/40">
	<div class="container flex justify-center px-6 py-2 font-semibold">
		<h1>Copyright Alessio Grespi 2024</h1>
		<!-- <h1>Contact: alessiogrespi@gmail.com</h1> -->
	</div>
</footer>