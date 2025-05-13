# Site Vinheria Agnello

Este é um website para um caso ficticio de um cliente: Sr. Giulio e sua loja de vinhos, vinheria Angello.
O caso envolve arranjar uma solução para fornecer aos clientes uma experiencia fiel ao que eles teriam an loja presencialmente, porem atraves de um e-commerce.

---

## https://guilhermesm-0808.github.io/Front_End-CP02/


## Estrutura projeto

```css
Front_End-CP01/
│
├── index.html
├── README.md
├── src/
│   ├── assets/
│   │   └── imgs/
│   │        ├── Home_page_imgs/
│   │        ├── Recomendações_imgs/
│   │        ├── bandeiras_imgs/
│   │        ├── Contato_imgs/
│   │        └── catalogo_imgs/
│   ├── css/
│   │   ├── efeitos.css
│   │   └── style.css
│   ├── js/
│   └── pages/
│       ├── pagina01.html
│       ├── pagina02.html
│       ├── pagine03.html
│       └── pagine04.html
```
### Index page (Home Page)

Pagina principal do site com navegação para as outras paginas do site pelo Header e Footer. Na pagina é apresentado resumidamente informações sobre a vinheria, os vinhos que se encontram na loja, uma foto da loja e um video apresentando um vinhedo nacional no fundo.

### Pagina01 (Recomendações)

Tabela de recomendações de vinhos, detalhendo tipo, sabor e preço.
Navegação para outras paginas no Header.

### Pagina02 (Catalogo)

Lista de vinhos para compra em blocos, apresentando uma imagem da garaffa, um botao de adicionar o carinho e um de comprar dentro de cada bloco do vinho.
Navegação para outras paginas no Header.

### Pagina03 (Sobre)

Pagina contando informações sobre a loja e sobre produtores e vinhedos parceiros/fornecedores da loja.
Navegação para outras paginas no Header.

### Pagina04 (Contato)

Paginá de contato, com um formulario pedindo Nome, email e por ultimo a mensagem para mandar para a loja.
Navegação para outras paginas no Header.

---

## Efeitos Visuais

### Pseudo-Classes
Novas pseudo classes foram adicionados ao footer, ":nth-child" na lista mudando a cor do texto para dar uma pequena diferença (branco e cinza-claro). ":visited" e ":active" mudando a cor do texto para destacar ao usuario oque está fazendo e oque já fez.

Um ":hover" foi adicionado a imagem no final da home page com uma transição lenta para aumentar a opacidade da imagem.

Sem mencionar os ":hover" já existentes na header, no menu de navegação, junto de uma transição suave, alterando a cor e tamanho do texto. 

### Pseudo-Elementos
"::selection" foi adicionado a paginá inteira para ter cores que condizem com a do site, combinando mais com o site ao invés das cores padrões azul e branco.

"::first-letter" foi utilizado na home-page para aumentar o tamanho da primeira letra de cada texto com um simples objetivo estético.


### Animações
@Keyframe animation adicionado na home page, após o primeiro texto as imagens dos galhos com uvas e a uva no centro foram animadas utilizando skew, translate e scale.

@Keyframe animation adicionado no catálogo dos vinhos com efeito de surgimento

Skew e translate nos galhos para parecerem que estão balançando com a base dos galhos relativamente fixos.

Translate e Scale no cacho de uvas no centro para parecer que está flutuando ou até mesmo pulando. 

Adição na pagina02 animações para o botão de ordenar preço e ordenar vendas, chamado pulse, que quando passa o mouse por cima ele fica pulsando
### Transições
Transições suaves adicionado no Header na barra de navegação, transição de 0.5s utilizando Hover na mudança de cor e tamanho do texto.

Transição de 16s adicionado na imagem no final da home-page aumentando a opacidade da imagem, assim aumentando o contraste da imagem e translate, scale e skew. Com a simples intenacao de possuir um efeito visual.

Transição adicionada em cada vinho com barras vermelhas indo da direita para esquerda em cima e embaixo

Foi adicionado a transição rotateY() nos botoes na pagina 03 com ajuda de pseudo-elementos, como exemplo o hover

Uma transição utlizando hover, onde vc passa o mouse por cima na tabela da pagina02  ele troca de cor em cada linha que vc passa o mouse.
### Transformações
Transform adicionado no logo para move-lo mais para o centro da tela e as opções de navegação na direita foram movidas um pouco mais para o centro e também "escalonados" com scale() para tornar o texto maior.



---

## Integrantes

### Miguel Manfré
https://github.com/MGmanfre

### Igor Nascimento
https://github.com/igornascimento-tech

### Joao Victor
https://github.com/Joao-toledo

### Vitor Pallis
https://github.com/Vitor12123

### Guilherme Satler Macedo
https://github.com/GuilhermeSM-0808
