<header>
	<h1>Bem-vindo ao Mundo dos Nerds</h1>
	<h2>Explore, leia e apaixone-se por novas histórias, filmes e personagens maravilhosos</h2>
</header>
<nav>
	<ul>
		<li><a href="/">Início</a></li>
		<li><a href="filmes">filmes</a></li>
		<li><a href="Livro">Livro</a></li>

	</ul>
</nav>

<div class="content">
	<h2>Livros em Destaque</h2>

	<div class="book-list">
		<div class="book">
			<img src="/fogo.jfif" alt="Capa do livro A Canção de Gelo e Fogo" />
			<h3>A Canção de Gelo e Fogo</h3>
			<p>Por George R.R. Martin</p>
			<a href="#">Leia Mais</a>
		</div>
		<div class="book">
			<img src="/1984.jfif" alt="Capa do livro 1984" />
			<h3>1984</h3>
			<p>Por George Orwell</p>
			<a href="#">Leia Mais</a>
		</div>
		<div class="book">
			<img src="/pripri.jfif" alt="Capa do livro O Pequeno Príncipe" />
			<h3>O Pequeno Príncipe</h3>
			<p>Por Antoine de Saint-Exupéry</p>
			<a href="#">Leia Mais</a>
		</div>
	</div>
</div>

<footer>
	<p>&copy; 2025 Mundo dos Livros - Todos os direitos reservados.</p>
</footer>

<style>
	/* Reset de estilo */
	body,
	h1,
	h2,
	p,
	ul,
	li,
	a {
		margin: 0;
		padding: 0;
		font-family: 'Arial', sans-serif;
	}
	body {
		background-color: #f0f0f0;
		color: #333;
		line-height: 1.6;
	}

	/* Header */
	header {
		background-color: #4caf50;
		color: white;
		padding: 20px;
		text-align: center;
	}

	header h1 {
		font-size: 3rem;
	}

	header h2 {
		font-size: 1.5rem;
		margin-top: 10px;
	}

	/* Navegação */
	nav {
		background-color: #333;
		overflow: hidden;
	}

	nav ul {
		list-style: none;
		padding: 0;
		margin: 0;
		display: flex;
		justify-content: center;
	}

	nav ul li {
		margin: 0 20px;
	}

	nav ul li a {
		color: white;
		text-decoration: none;
		padding: 10px 20px;
		display: block;
	}

	nav ul li a:hover {
		background-color: #575757;
	}

	/* Conteúdo Principal */
	.content {
		padding: 20px;
		text-align: center;
	}

	.book-list {
		display: flex;
		justify-content: space-around;
		flex-wrap: wrap;
		margin-top: 30px;
	}

	.book {
		background-color: #fff;
		border-radius: 8px;
		box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
		width: 200px;
		margin: 10px;
		text-align: center;
		padding: 10px;
	}

	.book img {
		width: 100%;
		border-radius: 5px;
		max-height: 300px;
		object-fit: cover;
	}

	.book h3 {
		font-size: 1.25rem;
		margin: 10px 0;
	}

	.book p {
		font-size: 1rem;
		color: #555;
	}

	.book a {
		display: inline-block;
		margin-top: 10px;
		padding: 10px 20px;
		background-color: #4caf50;
		color: white;
		text-decoration: none;
		border-radius: 5px;
	}

	.book a:hover {
		background-color: #45a049;
	}

	/* Rodapé */
	footer {
		background-color: #333;
		color: white;
		text-align: center;
		padding: 15px;
		margin-top: 30px;
	}
</style>
