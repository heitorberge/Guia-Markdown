# Guia de Markdown
Estou aprendendo linguagem **Markdown** no curso em Vídeo de *Git e Github*
~~Está frase tem um risco nom meio!~~
**Nome em Negrito**
*Nome em Itálico*
Podemos _*Misturar*_ configurações
___
# Título
## Título
### Título
#### Título
##### Título
###### Título Super pequeno
______
Criei uma linha! ⬆️
___
# Lista numerada:

1. Teste1
1. Teste2
   1.Teste2,1
1. Teste3

# Lista demarcada:

- Teste1
- Teste2
- Teste3
   - Teste3,1
   - Teste3,2
      - Teste3,2,1
- Teste4

#  Lista de Tarefas

- [x] Acordar
- [x] Comer
- [ ] Estudar (Estou de férias, pra que Estudar?)
---
# Imagem
![Sem título_edited](https://github.com/user-attachments/assets/fb0f03df-d5ae-4e36-bf3b-2dd09fb70032)

Que Imagem **Legal!**
___
# Link
[Acesse minha conta no Github](https://github.com/heitorberge)
___
# Tabela
Num | Nome | Nota
---|---|---
1 | Gustavo | 8,5
2 | José | 10,0
3 | Maria | 9,5

Que tabela Legal!
___
# Copiar Código
Olha meu Progama HTml
```
<!DOCTYPE html>
<html lang="pt-br">

<head>
<div id="interface">
	<meta charset="UTF-8"/>
	<link rel="stylesheet" type="text/css" href="_css/estilo.css"/>
		<title>GOOGLE GLASS </title>
	<style>
	</style>
</div>
</head>

<hgroup>
<body>
    <script>
        function mudaFoto(Foto) {
            document.getElementById("icone").src = foto;
        }
    </script>
	<header id="cabecalho">	
	<h1> GOOGLE GLASS</h1>
	<h2>A Revolução Do GOOGLE Está chegando</h2>
<figure>
	<img id="icone" src = "C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/glass.png"/>
</figure>
<br/>
<nav id="menu">
	<h1>Menu Principal</h1>
	<ul type="square">
		<li onmouseover="mudaFoto('C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/home.png') onmouseout="mudaFoto('_C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/glass.png')"><a href="index.html">Home<a/></li>
		<li onmouseover="mudaFoto('C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/espeficacoes.png') onmouseout="mudaFoto('C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/glass.png')"><a href="specs.html"> Especificações</a></li>
		<li onmouseover="mudaFoto('C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/Fotos.png') onmouseout="mudaFoto('C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/glass.png')"><a href="fotos.html"> Fotos</a></li>
		<li onmouseover="mudaFoto('C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/multimidia.png') onmouseout="mudaFoto('C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/glass.png')"><a href="multimidia.html">Multimídia</a></li>
		<li onmouseover="mudaFoto('C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/Contato.png') onmouseout="mudaFoto('C:/Users/Berg/Documents/Heitor Berg/curso-html5-pacote01 (1)/projeto-glass-html5/_media/_imagens/glass.png')"><a href="Comunique.html"> Fale conosco </a></li>
		<li><a href="ajuda.html">Ajuda/Help</a></li>
	</ul>
</nav>
</header>
</hgroup>

<section id="corpo">
<article id="np">
<hgroup>
<header id="np">
<h3>Tecnologia > &nbsp; Inovações</h3>

<h1>Saiba tudo sobre o Google Glass</h1>
<h2>Por Gustavo Guanabara e Heitor Berg</h2>
<h3 class="direita">Feito em 2024 e Notícias de 2013</h3>
<h3>Compre um glass na parte de Ajuda</h3>
<h3>obs:Leia a parte AJUDA</h3>

</header>
</hgroup>
<h2>O que é</h2><br/>
<p>O <Strong><i>Google Glass</i></Strong> é um acessório em forma de óculos que possibilita a interação dos usuários com diversos conteúdos em realidade aumentada. Também chamado de <strong><a href="https://pt.wikipedia.org/wiki/Project_Glass" target="_blank">Project Glass</a></strong>, o eletrônico é capaz de tirar fotos a partir de comandos de voz, enviar mensagens instantâneas e realizar vídeoconferências. Seu lançamento está previsto para 2014, e seu preço deve ser de US$ 1,5 mil. Atualmente o <strong><em>Google Glass</em></strong> encontra-se em fase de testes e já possui um vídeo totalmente gravado com o dispositivo. Além disso, a companhia de buscas registrou novas patentes anti-furto e de desbloqueio de tela para o acessório.</p>
<iframe width="300" height="200" src="https://www.youtube.com/embed/elXk87IKgCo?si=ETsacA9_BJOpoSlp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<figcaption>Uma nova maneira de ver o mundo</figcaption>
<h2>Data de lançamento</h2><br/>
<p>Não há uma data específica e oficial para o dispositivo ser lançado, ainda. Pode ser que ele esteja disponível em demonstrações a partir de 2013, mas seu lançamento para as lojas fica para, pelo menos, 2014.</p>

<h2>Especificações Técnicas<br/></h2>
<table id="tabela">
<caption>Tabela Técnica do Google Glass <span>Mar/2013</span></caption>

<tr><td class="ce">Tela</td><td class="cd">Resolução equivalente a tela de 25°</td></tr>
<tr><td rowspan="2" class="ce">Camera</td><td class="cd"> 5MP para fotos   </td></tr>
<tr><td class="cd">720p para vídeos </td></tr>
<tr><td rowspan="2" class="ce">Conectividade</td><td class="cd"> Wi-Fi</td></tr>
<tr><td class="cd"> Bluetooth</td><td>
<tr><td class="ce">Memória Interna</td><td class="cd">12GB</td></tr>
</table>

<p>De acordo com fontes próximas do <strong>Google</strong>, os óculos vão contar com uma pequena tela de LCD ou AMOLED na parte superior e em frente aos olhos do usuário. Com o uso de uma câmera e GPS, você pode se situar, assim como selecionar opções com o movimento da cabeça</p>

<p>O vídeo de divulgação do <strong>Google</strong> mostra que você pode se transformar em uma espécie de <i>“super-humano”</i>, já que o aparelho pode indicar a quantos metros você está de seu destino, se o metrô está aberto ou fechado, mostrar o clima, agenda e até mesmo permitir que você marque encontros apenas com comandos de voz.</p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/ErpNpR3XYUw?si=YZIDr1yZx7KkUxIw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</article>
</section>

<aside id="lateral">

<h1>Outras Notícias<br/></h1>
<h2>Vídeo mais recente</h2>
<iframe width="560" height="315" src="https://www.youtube.com/embed/eo29M8Yk3Qc?si=ZEMZJp1R2m1mExTk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<h2>Novidades no Glass<br/></h2>
<p>O <Strong>Google</strong> enfim revelou as especificações completas do <i>Google Glass</i>, e com ele uma surpresa ainda inédita no mercado: a gigante das buscas usará um sistema de áudio baseado na transdução por condução. Através das hastes dos óculos, o som será transmitido para o ouvido do usuário por meio de microvibrações em determinados ossos de sua cabeça, sem usar nenhum tipo de alto-falante.</p>
<p>Além da surpresa do áudio, a tela montada a frente do olho do usuário também chamou atenção. Serão 640 x 360 pixels de resolução que, em proporção, equivaleria a um monitor de 25 polegadas de alta definição colocado a 2,5 metros de distância do espectador.</p>
</aside>
<footer id="rodape">
<p>Copyright &copy; 2013 - by Gustavo Guanabara and Heitor Berg<br/>
<a href="http://facebook.com/cursoemvideo" target="_blank">Facebook</A> |<a href="http://twitter.com/cursoemvideo" target="_blank">Twitter</a></p>
</footer>
</div>
</body>
</html>

```
Que legal!
Para ver o Código no meu perfil [clique aqui](https://github.com/heitorberge/PROJETO-GLASS)
___
# CÓDIGO
`var b = 5  
var c = 3  
var a = b - c   
c = a - b  
a = b - c`
Gente eu escrevi esse código em algoritimo e esqueci o valor da var a
Qual é o valor dela?
______


> # _**Guia da Linguagem Markdown**_
> @joaohsantanaoc 

Que Legal sua postagem!
