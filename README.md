---
<div align="center">

# Desafio das paradas 13 e 14



![HTML](https://img.shields.io/badge/HTML-F16529?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-264de4?&style=for-the-badge&logo=css3&logoColor=white)


</div>


<p>Este projeto é um menu hamburger apenas com CSS. Existem duas versões - uma com o menu da direita e um com o menu na esquerda.</p>


<div align="right">

[menu-esquerda](/menu-hamburger-esquerda/) & [menu-direita](/menu-hamburger-direita/)

</div>

## index.html

O arquivo `index.html` é a página principal que contém a estrutura do menu hamburger. É idêntico para as duas versões - esquerda e direita - Ele inclui um `nav` elemento com um `div` para o botão do menu hamburger e um `ul` para os itens do menu. O arquivo também linka para o arquivo `style.css` para estilização.

```
<body>
<nav role="navigation">
    <div id="menuToggle">
      <input type="checkbox"/>
      <span></span>
      <span></span>
      <span></span>
      <ul id="menu">
        <a href="#"><li>Home</li></a>
        <a href="#"><li>Sobre</li></a>
        <a href="#"><li>Info</li></a>
        <a href="#"><li>Contato</li></a>
        <a href="#" target="_blank"><li>a</li></a>
      </ul>
    </div>
  </nav>
</body>

```

### style.css - esquerda

O arquivo `style.css` contém os estilos para a página. Ele define estilos para o corpo da página, o botão do menu hamburger e os itens do menu. Quando o botão do menu hamburger é clicado, ele aplica transformações CSS para abrir o menu.

Aqui estão alguns detalhes sobre o que cada seção do código faz:

- `*`: Este seletor universal redefine a margem, o preenchimento e a caixa de dimensionamento para todos os elementos na página para garantir a consistência em diferentes navegadores.

- `body`: Define a margem, o preenchimento, a cor de fundo, a cor do texto e a fonte para o corpo da página.

- `#menuToggle`: Estiliza o botão do menu hamburger. Ele é posicionado relativamente no topo da página e à esquerda.

- `#menuToggle a`: Define a cor e a decoração do texto para os links no menu. Ele também adiciona uma transição para mudar a cor quando o link é passado sobre.

- `#menuToggle input`: Estiliza a caixa de seleção que controla se o menu está aberto ou fechado. Ele é posicionado absolutamente dentro do botão do menu hamburger e é transparente para que não seja visível.

- `#menuToggle span`: Estiliza as linhas do botão do menu hamburger. Eles são posicionados relativamente dentro do botão do menu hamburger e transformados para criar o efeito de "hamburger" quando o menu está fechado e o efeito de "X" quando o menu está aberto.

- `#menu`: Estiliza o menu em si. Ele é posicionado absolutamente e transformado para mover para a esquerda quando o menu está fechado e para a direita quando o menu está aberto.

- `#menu li`: Define o preenchimento e o tamanho da fonte para os itens do menu.


### style.css - direita
    
- `#menuToggle`: Na versão do menu à direita, o botão do menu hamburger é posicionado absolutamente no topo da página e à direita, em vez de à esquerda como na versão do menu à esquerda.

- `#menuToggle input`: A caixa de seleção que controla se o menu está aberto ou fechado é posicionada absolutamente dentro do botão do menu hamburger e à direita, em vez de à esquerda como na versão do menu à esquerda.

- `#menu`: O menu é posicionado absolutamente e transformado para mover para a direita quando o menu está fechado e para a esquerda quando o menu está aberto. Isso é o oposto da versão do menu à esquerda, onde o menu se move para a esquerda quando está fechado e para a direita quando está aberto.

- A cor de fundo do menu na versão direita é `#ededed`, enquanto na versão esquerda é `#e0d7c6`.

## Contribuição
Você pode contribuir fazendo um fork deste repositório e abrindo um PR ou comentando algo em `issue`

## Licença

Este projeto é licenciado sob a licença MIT.

</div>