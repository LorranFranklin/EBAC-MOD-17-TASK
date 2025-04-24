## Neste exercício você deverá:

1. Converter o estilo do projeto disponibilizado no Material de apoio para o LESS;
2. Utilizar os recursos do LESS que aprendeu durante o módulo:

   variáveis;
   divisão dos arquivos;
   escapings;
   mapas.

3. Crie uma branch chamada exercicio_less no repositório do curso.
4. Armazene os arquivos LESS nesta branch.
5. Envie o link da branch através da plataforma.

## Vamos iniciar o projeto criando um repositório no github

## Após isso iniciamos o git com os arquivos disponibilizados e abertos no vs code.

## Instalando o less no nosso projeto

```
npm install --save-dev less
```

## Iniciando o less

```
npm init
```

## Daremos enter nas perguntas que irão nos aparecer

## Instalando whatch compiler

```
npm i --save-dev less-watch-compiler
```

## Agora vamos mudar o script em `package.json` precisamos criar o caminho, suas pastas e arquivo.

```
  "scripts": {
    "less": "less-watch-compiler ./src/styles ./build/styles main.less",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```

Após isso criaremos as pastas `src` que irá conter `styles`. Depois criaremos `build` que irá conter `styles` e o arquivo que será compilado será o `main.less`. O Caminho deve ser o mesmo do script acima.

## Vamos ao terminal

```
npm run less
```
## Trocando as cores do svg em images
Vamos abrir o ```svg``` como arquivo de texto.  
Vamos até o ```svg```, clicamos com o ```botão direito do mouse```, ```abri com```, ```editor de texto```
Após isso vamos procurar por: ```stroke="#44bd32"``` e colocamos a cor de nossa escolha.
