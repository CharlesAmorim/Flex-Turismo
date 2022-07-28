<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flex Turismos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
	<div class="flex-container menu">

        <div><h1>FlexTurismos</h1></div>
    	
    	<ul class="list-items">
            <li><a href="#quem-somos">Quem Somos</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#planos">Planos</a></li>
        </ul>
    </div>	
    </header>
    
    <div class="flex-container apresentação">
        <div class="texto-apresentação">
            <h1>Flex <br>Turismos</h1>
            <p>O melhor serviço para você!</p>
            <a href="" class="btn">Saiba Mais!</a>
        </div>
    
        <div>
            <div><img src="./images/0-main.png" alt="banner de apresentação"></div>
        </div>
    </div>
    
    <div class="flex-container" id="quem-somos">
        <div>
            <img src="./images/1-quem-somos.png" alt="balcão de atendimento">
        </div>
    
        <div>
            <h2>Quem somos</h2>
            <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. </p>
            <p>The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English.</p>
        </div>
    </div>
    
    <div class="container-externo">
    	<div class="flex-container" id="servicos">
    		<div>
    			<h2>Serviços</h2>
    		</div>
    
    		<div class="list-servicos">
    			<div class="items-servicos">
    				<div><img src="./images/icon-2.png" alt="hospedagens"></div>
    				<p>Hospedagens</p>
    				<a href="#">Comprar Agora</a>
    			</div>
    
    			<div class="items-servicos">
    			   <div><img src="./images/icon-1.png" alt="pacote de viagens"></div>
    			   <p>Pacotes de viagens</p>
    			   <a href="#">Comprar Agora</a>
    			</div>
    
    			<div class="items-servicos">
    				<div><img src="./images/icon-3.png" alt="roteiros personalizados"></div>
    				<p>Roteiros personalizados</p>
    				<a href="#">Comprar Agora</a>
    			</div>
    
    		</div>
    	</div>
    </div>
    
    <div class="flex-container" id="planos">
    	
    	<div><h2>Planos</h2></div>
    	
    	<div class="list-planos">
    		<div class="item-plano">
    			<h3>Plano 1</h3>
    			<ul>
    				<li>Suporte 24h</li>
    				<li>Serviços de quarto</li>
    				<li>Guia turístico</li>
    			</ul>
    			<a href="#" class="btn">Saiba Mais!</a>
    		</div>
    
    		<div class="item-plano">
    			<h3>Plano 2</h3>
    			<br>
    			<ul>
    				<li>Suporte 24h</li>
    				<li>Serviços de quarto</li>
    				<li>Guia turístico</li>
    				<li>Roteiro de trilhas</li>
    				<li>Serviço personalizado</li>
    			</ul>
    			<a href="#" class="btn">Saiba Mais!</a>
    		</div>
    
    		<div class="item-plano">
    			<h3>Plano 3</h3>
    			<br>
    			<ul>
    				<li>Suporte 24h</li>
    				<li>Serviços de quarto</li>
    				<li>Guia turístico</li>
    				<li>Roteiro de trilhas</li>
    				<li>Serviço personalizado</li>
    				<li>Área Vip</li>
    			</ul>
    			<a href="#" class="btn">Saiba Mais!</a>
    		</div>
    	</div>	
    </div>
    
    <footer>
    	<div class="flex-container footer">
    		<p>&copy; 2021 CSS Flexbox</p>
    		<p>Desenvolvido por: Charles Amorim</p>
    	</div>	
    </footer>
</body>
</html>

