# Site estático do Encontros Pythônicos

Este é o site de apresentação do projeto de extensão Encontros Pythônicos hosteado utilizando o Github pages.

Para a geração de html o site utiliza a linguagem de marcação [Asciidoc](https://docs.asciidoctor.org/asciidoc/latest/) pela sua consistência e ferramentas que já vem em conjunto

As páginas html são apenas uma projeção os arquivos de conteúdo de fato estão na pasta **src/**

## Como gerar o html

Para transformar os arquivos .adoc em html segue-se os seguintes passos:

1. Tenha as ferramentas cli de aciidoc instaladas no seu computador: [Asciidoctor](https://docs.asciidoctor.org/asciidoctor/latest/install/)

2. Com a ferramenta instalada basta usar o seguinte comando na pasta raíz do repositório para gerar o html

```bash
asciidoctor -D ./ -a linkcss src/*.adoc
```

## Como alterar o site

Para modificar o site basta modificar ou adicionar os arquivos .adoc na pasta /src, quando salvar o arquivo basta gerar o html novamente.

## Estilo do site

Todo o estilo do site está no arquivo style.css


