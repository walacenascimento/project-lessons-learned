# Project-lessons-learned

## Boas vindas ao projeto Lições Aprendidas!

## Sumário

- [Habilidades](#habilidades)
- [Desafio](#desafio)
- [Instruções](#instruções)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Status](#status)
- [Desempenho](#desempenho)
- [Colaborador](#colaborador)
- [Observações](#observações)
- [Lista de requisitos](#lista-de-requisitos)
- [Requisitos Bônus](#requisitos-bônus)

## Habilidades

* Utilizar _HTML_ para construir páginas WEB.
* Utilizar _HTML_ semântico para tornar sua página mais acessível e melhor ranqueada.
* Utilizar _CSS_ para adicionar estilo e posicionar elementos.

## Desafio

Desenvolver um site contendo uma série de informações sobre o que foi aprendindo sobre HTML e CSS. Um site com elementos posicionados e estilizados com semântica apropriada para que seja acessível e melhor ranqueado.

## Instruções

1. Clonar o repositório:
  * `git clone git@github.com:walacenascimento/project-lessons-learned.git`.

2. Instalando as dependências:
  * `npm install`

3. Rondando o projeto:
  * Para rodar o projeto no navegador foi utilizado a extensão `Go Live` do `VSCode`

### Linter

Neste projeto, foi utilizar os linters `ESLint` e `StyleLint`, com o objetivo de garantir a qualidade do código, assim como
alinhar-se com as boas práticas de desenvolvimento.
Para rodá-los localmente no projeto, execute os comandos abaixo:

```bash
npm run lint
npm run lint:styles
```

Executado o comando `npm run lint:styles`, irá avaliar se os arquivos com a extensão `CSS` estão com o padrão correto.

Executado o comando `npm run lint`, irá avaliar se os arquivos com a extensão `JS` e `JSX` estão com o padrão correto.

  ### Cypress

Cypress é uma ferramenta de teste de front-end desenvolvida para a web.

Para executar os testes apenas no terminal:

```bash
npm test
```

Para executar os testes e vê-los rodando em uma janela de navegador:

```bash
npm run cypress:open
```

***ou***

```bash
npx cypress open
```
Após executar um dos dois comandos acima, será aberta uma janela de navegador, então basta clicar no nome do arquivo de teste que quiser executar
ou para executar todos os testes clique em Run all specs

**Para rodar o cypress é preciso ter rodado o comando npm install anteriormente.**

 ### Tecnologias Utilizadas:
1. `HTML e CSS`

### Status:
 - `Finalizado` - `APROVADO`

### Desempenho:
  * `100%`

### Colaborador:
* Colaborador(es,as)
    * Este projeto foi desenvolvido individualmente por mim, `Walace Nascimento`

### Observações:
- Tanto os linters quanto o cypress, foram configurados pela <a href="https://betrybe.com">`Trybe`</a>
- Todos os teste desse projeto foram implementandos pela <a href="https://betrybe.com">`Trybe`</a>

## Lista de requisitos:

- [x] 1. Adicione uma cor de fundo específica para a página

A página deve possuir cor de fundo: rgb(253, 251, 251)

- [x] 2. Adicione uma barra superior com um título

A barra deve possuir o ID "cabecalho" e deve ser fixa no topo da página com a propriedade top tendo **0**. O título deve estar dentro da barra e ser um elemento **h1** com ID "titulo".

- [x] 3. Adicione uma foto sua à página

A foto deve ser inserida utilizando uma tag **img** com o ID "minha_foto".

- [x] 4. Adicione uma lista de lições aprendidas à página

A lista deve possuir **10** itens, ser numerada e possuir o ID "licoes_aprendidas".

- [x] 5. Crie uma lista de lições que ainda deseja aprender para a página

A lista deve possuir **10** itens, não ser numerada e possuir o ID "licoes_a_aprender".

- [x] 6. Adicione um rodapé para a página

O rodapé deve utilizar a tag **footer** e possuir o ID "rodape".

- [x] 7. Insira pelo menos um link externo na página

A configuração desse link deve ser feita para abrir em uma nova aba do navegador

- [x] 8. Crie um artigo sobre seu aprendizado

O artigo deverá possuir mais de 300 **caracteres** e menos de 600, além disto deve possuir a tag **article**.

- [x] 9. Crie uma seção que conta uma passagem sobre seu aprendizado

A seção deverá possuir mais de 100 **caracteres** e menos de 300, além disto deve possuir a tag **aside**.

- [x] 10. Aplique elementos HTML de acordo com o sentido e propósito de cada um deles

Para tornar o seu site mais acessível e melhorar seu ranqueamento em mecanismos de busca na Web, sua página deve conter os seguintes elementos: article, header, nav, section, aside e footer.

- [x] 11. Teste a semântica da sua página está aprovada pelo site CodeSniffer


### Requisitos Bônus

- [x] 12. Adicione uma tabela à página

A página deve possuir uma tabela

- [x] 13. Utilize o Box model

Altere **margin**, **padding** e **border** dos elementos para ver, na prática, como esses atributos influenciam e melhoram a visualização dos componentes.

- [x] 14. Altere atributos relacionados as fontes

Modifique o estilo da sua tipografia alterando o tamanho de letra, a cor, o espaçamento entre as linhas e a **font-family**.

- [x] 15. Posicione o seu artigo e a seção sobre aprendizados um ao lado do outro

Adicione ao elemento posicionado no lado esquerdo a classe "lado-esquerdo" e ao elemento posicionado no lado direito a classe "lado-direito"
