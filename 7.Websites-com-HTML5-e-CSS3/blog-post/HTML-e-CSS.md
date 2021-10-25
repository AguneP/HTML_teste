# O Que é HTML

- HTML significa **H**yper **T**ext **M**arkup **L**anguage;
- Documentos HTML usam tags de HTML;
	<h1>	<p>	<a>

- tags marcam o começo e fim de um elemento;
	<tagname>coment</tagname>

# O Que é CSS

- CSS significa **C**ascading **S**tyle **S**heets;
- CSS define exatamente a aparencia HTML;
- HTML é o conteúdo;
- CSS é o estilo(style);

## Diferentes maneiras de escrever CSS:

1. Dentro de uma tag HTML, ou seja, **inline**;
2. Dentro de um documento HTML, ou seja, **interno**;
3. Em um arquivo CSS, ou seja, **externo**;

## Cores

### O Modelo RGB *(Red, Green, Blue)*

* RRGGBB
Para cada cor:
 	- Min: 0 (hex 0)
 	- Max: 255 (hex ff)

### Tranparência com RGBA
Se escreve en decimal:
	- rgba(29,167,23,0.75) --> verde com 75% de transparencia

## CSS Box Model[^1]

* **Conteúdo:** texto, imagens, etc.;
* **Padding(preenchimento):** área ao redor do conteúdo dentro da caixa;
* **Fronteira:** ao redor do padding e do conteúdo;
* **Margem:** espaço entre caixas;

## Construindo Layouts

1. Usando os atributos do Box Model, ajustando o width e o hight;
2. Usar *text-align, margin, padding, border e **float***;
3. Float é a capacidade de um elemento estar ao lado do outro;
4. Clear é o oposto do float; 

# Web Design

Aqui mostrarei algumas dicas de web disign mostradas no curso:

## Tipografia

1. Usar um tamanho de fonte entre 15px e 25px;
2. Usar tamanhos de fonte (bem) grandes para cabeçalhos;
3. Usar um espaçamento entre linhas entre 120% e 150%;
4. Ter de 45 a 90 caracteres por linha;
5. Usar boas fontes.

Como escolher uma fontes[^3]:
* Escolha uma que reflita o estilo que quer para seu site;
* Decida: sans-serif ou serif;
* Use boas fontes;
* Use somente uma fonte.

## Cores

1. Use somente uma unica cor básica[^4];
2. Se for usar mais de uma cor, utiliza uma ferramenta[^5];
3. Use cores para chamar atenção;
4. Nunca utiliza preto no seu design;
5. Escolha sabiamente as cores;

## Imagens[^2]

1. Coloque texto diretamente na imagem (precisa de contraste);
2. Sobrepor a imagem (com uma cor);
3. Colocar o texto em uma caixa;
4. Colocar um desfoque na imagem;
5. Debotamentar a imagem no "pé";

## Ícones[^2]

1. Use ícones para listar recursos/passos;
2. Use ícones para ações e links
	- Os ícones devem ser reconheciveis;
	- Rotule os seu ícones; 
3. Ícones não devem assumir o centro do palco;
4. Use ícones de fontes quando possível*(**Static** image X **Vector** icon font)*;

## Spacing and Layout

1. Usar *"whitespace"*
	* Colocar *whitespace* entre os elementos;
	* Colocar *whitespace* entre os grupos de elementos;
	* Colocar *whitespace* entre as seções do *website*;
	* Não exagere;

2. Define hierarquia
	* Defina onde quer que os visitantes olhem primero;
	* Estabeleca um flow que corresponde à mensagem do seu conteúdo;
	* Use *whitespace* para contruir esse flow;

## User Experience[^2]

A **interface do usuário** é a apresentação de um produto, como ela se parece e se sente;



[^1]: [Box Model](https://subscription.packtpub.com/book/web_development/9781788395038/6/ch06lvl1sec52/css-box-model)
[^2]: [Recurso de Jonas Schmedtmann](http://codingheroes.io/resources/)
[^3]: [Google Fonts](https://fonts.google.com/?preview)text=the+quick+brown+fox+jumps+over+the+lazy+dog&preview.text_type=custom
[^4]: [Flat Colors UI](https://flatuicolors.com/) & [Oto255](https://www.0to255.com/)
[^5]: [Adobe Color CC](https://color.adobe.com/pt/create/color-wheel) & [Paletton](https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF)