![dev-dependencies](https://david-dm.org/brunoalv-s/devkit-jekyll-template/dev-status.svg)
DevKit Template (Jekyll, Jade, SASS & BrowserSync.)
==========================================

Este é um projeto de Kit de Desenvolvimento inicial para projetos usando `Jekyll`, `SASS`, `Jade`, `GulpJS` & `BrowserSync`.

Os diretórios dos arquivos `Sass` estão organizados seguindo as instruções da arquitetura `ITCSS` e da metodologia `RSCSS`.

----
**PS:** Pretendo manter este repositório com o conteúdo em português. Visto que conteúdo encontrado na internet, ainda é muito escasso - ainda mais quando o assunto é Desenvolvimento Web.

## Requisitos Básicos

Para usar este projeto, você vai precisar de algumas coisas instaladas no seu ambiente.

1. [Jekyll](http://jekyllrb.com/)
2. [NodeJS](http://nodejs.org)
3. [Gulp](https://github.com/gulpjs/gulp)

## Instalação Local

1. Clone este repositório ou apenas faça o download para um diretório de sua escolha.
2. Dentro do diretório, rode: `npm install`.

## Como usar

Levando em consideração que você já tem o NodeJS instalado na sua máquina (~~Sério que ainda não tem?~~), abra seu terminal no diretório do projeto e rode:
```shell
$ npm install
$ gulp
```
Isso irá rodar o `GulpJS` e seguirá as instruções deixadas no arquivo `gulpfile.js`.
Ele irá compilar os arquivos .sass na pasta `assets/sass`, os arquivos .jade em `_jadefiles`, rodar o parâmetro do Jekyll para servir o site estático em `_site` e enfim o `browserSync`.

Pronto, você já está pronto para botar a mão na massa.

## Dica para usuários do Windows 10

Essa dica foi compartilhada pelo [Willian Justen](https://github.com/willianjusten) para usuários do `Windows 10`(~~infelizmente é meu caso.~~), onde é preciso fazer uma mudança no [gulpfile.js](https://github.com/brunoalv-s/DevKit/blob/master/gulpfile.js#L15) substituindo a linha para `return cp.spawn('jekyll.bat', ['build'])`. Sem fazer essa mudança eu não havia conseguido rodar as tarefas do `GulpJS`. :()

## Agradecimentos

Levei como base os projetos de [Shane Osbourne](https://github.com/shakyShane), [Willian Justen](https://github.com/willianjusten) e [Travis Neison](https://github.com/travisneilson/) para chegar ao resultado final, então deixo o meu muito obrigado a vocês por compartilhar esse tipo de conhecimento que é tão importante para muitos. Espero um dia poder recompensá-los e até ajudar outras pessoas, assim como vocês fizeram por mim.

E um sincero obrigado [onedaylove](https://github.com/onedaylove) por me ajudar a solucionar um problema.

Espero não ter esquecido ninguém.
