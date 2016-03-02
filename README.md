DevKit - Jekyll, Jade, SASS & BrowserSync.
==========================================

Este é um projeto de Kit de Desenvolvimento inicial para projetos usando `Jekyll`, `SASS`, `Jade`, `GulpJS` & `BrowserSync`.

Os diretórios dos arquivos `Sass` estão organizados seguindo as instruções da arquitetura `ITCSS` e da metodologia `RSCSS`.

*PS: Pretendo manter este repositório com o conteúdo em português. Visto que conteúdo encontrado na internet, ainda é muito escasso - ainda mais quando o assunto é Desenvolvimento Web.*

## Requisitos Básicos

Para usar este projeto, você vai precisar de algumas coisas instaladas no seu ambiente.

1. [Jekyll](http://jekyllrb.com/)
2. [NodeJS](http://nodejs.org)
3. [Gulp](https://github.com/gulpjs/gulp)

## Instalação Local

1. Clone este repositório ou apenas faça o download para um diretório de sua escolha.
2. Dentro do diretório, rode: `npm install`.

## Como usar

Abra seu terminal no diretório do projeto e rode:
```shell
$ gulp
```
Isso irá rodar o `GulpJS` e seguirá as instruções deixadas no arquivo `gulpfile.js`.
Ele irá compilar os arquivos .sass na pasta `assets/sass`, os arquivos .jade em `_jadefiles`, rodar o parâmetro do Jekyll para servir o site estático em `_site` e enfim o `browserSync`.

Pronto, você já está pronto para botar a mão na massa.
