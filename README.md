# t180

<html lang="pt-br">
	<head>
		<title>Html Aula 10 - Seleções</title>
		<title>Formulario</title>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width initial-scale=1"><!-- Conceito de tabelles e css também fica com o layout mais semantico também.-->
		<!--Link do arquivo do style.css-->
		<link rel="stylesheet" type="text/css" href="css/Style2.css">
		</head>
	<body>
        <form method="post">
        <header>
            <h2> Site topzera </h2>  
        </header>

        <section>
            <nav>
                <ul>
                 <h2>Sites - HTML</h2>
                    <li><a href="./11-Prova-avaliativa.html">Home</a></li>
                    <li><a href="./01-frase.html">Frase</a></li>
                    <li><a href="./02-listas+sub-nivel.html">Listas+Sub-Nivel</a></li>
                    <li><a href="./03-tabelas.html">tabelas</a></li>
                    <li><a href="./04-tabelas-atividades.html">Atividade-Tabela</a></li>
                    <li><a href="./05-diagracao+menu.html">Diagramação+Menu</a></li>
                    <li><a href="./06-Meio Markenting.html">Meio Markenting</a></li>
                    <li><a href="./07-tabelas-moldes.html">Tabelas-moldes</a></li>
                    <li><a href="./08-Dia da mulher.html">Dia da mulher</a></li>
                    <li><a href="./09-Formulario.html">Formulario</a></li>
                    <li><a href="./10-selecoes.html">Seleções</a></li>  
                <h2> Redes sociais</h2>
                <li><a href=" https://www.instagram.com/invites/contact/?i=7daz34g091p1&utm_content=2ecaj93">Link do Instagram</a></li>

                </ul>
			</nav>
			</section>
    	</form>
	</body>
			<article>
				<ul>
					<li><a href="./06-Diagramacao+Menu.Html">Home</a></li>
					<li><a href="#sobre">Sobre</a></li>
					<li><a href="#contato">Contato</a></li>
					<li><a href="./08-selecoes.html">Tipos de Selecionar Itens</a></li>
				</ul>
				<form method="post">
            <div>
                <h4> Seleção Simples </h4>
                    <label>Qual estação do ano você gosta?</label>
                    <input type="radio" name="estacao" values="primavera"> Primavera
                    <input type="radio" name="estacao" values="verao"> Verão 
                    <input type="radio" name="estacao" values="outono"> Outono
                    <input type="radio" name="estacao" values="inverno"> Inverno
           </div>
           <div>
                <h4> Seleção Multipla </h4>
                    <label>Quais times preferidos?</label>
                    <input type="checkbox" name="time" value="cruzeiro"> cruzeiro
                    <input type="checkbox" name="time" value="galinha"> galinha
                    <input type="checkbox" name="time" value="ameriaca"> ameriaca
                    <input type="checkbox" name="time" value="palmeiras"> palmeiras
                    <input type="checkbox" name="time" value="santos"> santos 
           </div>
           <div>
                <h4> Lista de seleção </h4>
                    <label>Qual a sua cor preferida?</label>
                    <select>
                    <option value="azul">Azul</option>
                    <option value="amarelo">Amarelo</option>
                    <option value="vermelho">Vermelho</option>
                    <option value="preto">Preto</option>
                    <option value="branco" selected>branco</option>
                    </select>

           </div>
					<div>
					<p>
						<input type="submit">
					</p>
					</div>	
				</form>
			</article>
		</section>
		<footer>
			<h3>Desenvolvido por @DDeus</h3>
		</footer>
	</body>
</html>
