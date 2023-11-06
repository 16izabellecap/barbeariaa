# barbeariaa
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Produtos - Barbearia Alura</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style.css">
	</head>
	<body>
		<header>
			<div class="caixa">
				<h1><img src="logo.png"></h1>

				<nav>
					<ul>
						<li><a href="index.html">Home</a></li>
						<li><a href="produtos.html">Produtos</a></li>
						<li><a href="https://github.com/16izabellecap">Contato</a></li>
                        <li><a href="https://www.youtube.com">Youtube</a></li>https://github.com/16izabellecap/barbeariaa/tree/2f2b3315540d6e0c8ab7ea175370cfcdea30511a
					</ul>
				</nav>
			</div>
		</header>

		<main>
			<ul class="produtos">
				<li>
					<h2>Cabelo</h2>
					<img src="cabelo.jpg">
					<p class="produto-descricao">Na tesoura ou máquina, como o cliente preferir</p>
					<p class="produto-preco">R$ 25,00</p>
				</li>
				<li>
					<h2>Barba</h2>
					<img src="barba.jpg">
					<p class="produto-descricao">Corte e desenho profissional de barba</p>
					<p class="produto-preco">R$ 18,00</p>
				</li>
				<li>
					<h2>Cabelo + Barba</h2>
					<img src="cabelo+barba.jpg">
					<p class="produto-descricao">Pacote completo de cabelo e barba</p>
					<p class="produto-preco">R$ 35,00</p>
				</li>
			</ul>
		</main>

		<footer>
			<img src="logo-branco.png">
			<p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
		</footer>
	</body>
</html>






header {
	background: #BBBBBB;
	padding: 20px 0;
}

.caixa {
	position: relative;
	width: 940px;
	margin: 0 auto;
}

nav {
	position: absolute;
	top: 110px;
	right: 0;
}

nav li {
	display: inline;
	margin: 0 0 0 15px;
}

nav a {
	text-transform: uppercase;
	color: #000000;
	font-weight: bold;
	font-size: 22px;
	text-decoration: none;
}

nav a:hover {
	color: #C78C19;
	text-decoration: underline;
}

.produtos {
	width: 940px;
	margin: 0 auto;
	padding: 50px 0;
}

.produtos li {
	display: inline-block;
	text-align: center;
	width: 30%;
	vertical-align: top;
	margin: 0 1%;
	padding: 30px 20px;
	box-sizing: border-box;
	border: 2px solid #000000;
	border-radius: 10px;
}

.produtos li:hover {
	border-color: #C78C19;
}

.produtos li:active {
	border-color: #088C19;	
}

.produtos li:hover h2 {
	font-size: 34px;
}

.produtos h2 {
	font-size: 20px;
	font-weight: bold;
}

.produto-descricao {
	font-size: 18px;
}

.produto-preco {
	font-size: 22px;
	font-weight: bold;
	margin-top: 10px;
}

footer {
	text-align: center;
	background: #000000;
    margin-top: 20px 20px 20px;
	padding: 40px 0;
}

.copyright {
	color: #FFFFFF;
	font-size: 13px;
	margin: 20px 0 0;
}
