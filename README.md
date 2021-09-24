# EAD PLATAFORM
  - Desenvolvimento de Plataform de Ensino a Distância voltada ao ensino fundamental.

## REQUISITOS
  - XAMPP (https://www.apachefriends.org/pt_br/index.html)
    - PHP >= 7.2v
    - MySQL
  - Composer (https://getcomposer.org/)
  - Git (https://git-scm.com/downloads)

## COMO CRIAR UM PROJETO LARAVEL
  - Com todas as ferramentas acima instaladas, podemos utilizar o composer para criar nosso projeto.
  ``` composer create-project laravel/laravel example-app ```
  [video-criação-do-projeto](https://watch.screencastify.com/v/pDT7ckEXBu7S4kCYkPy1)

## EXECUTANDO PROJETO
  - Com a base do projeto instalada no passo anterior, e com o arquivo aberto no Visual Studio Code como pasta raiz, podemos executar o comando de start do laravel:
  ``` php artisan serve ```   
  [video-startando-o-projeto](https://watch.screencastify.com/v/x4fMa459P9zBL16iN1mn)

## CRIANDO AS PRIMEIRAS PÁGINAS
  - Todas as páginas ficam dentro de resources/views, e o roteamento(redirecionamento entre as páginas) é controlado pelo arquivo routes/web.php
  [video-criando-paginas](https://watch.screencastify.com/v/e1azkWACXTSxc7hCo93l)
  [video-criando-rotas](https://watch.screencastify.com/v/65HnWRy2v4P43Q20OLeb)

## ENVIO DE FORMULÁRIOS
  - Para respeitar o padrão MVC(Model, View e Controller), e para ter um melhor encapsulamento de código o ideal é que as views não sejam retornadas direto pelo web.php, mas que o web chame funções que estão dentro de App\Http\Controllers e essa funções cuidaram da renderização das telas.
  - Em web vimos também que estaremos utilizando principalmente dois métodos de requisição HTTP, que são GET e POST, a principal diferença entre eles é que GET suporta apenas informações enviadas via URL(ou seja todos os dados enviados por GET aparencem na url do navegador) e o POST conseguem enviar uma maior quantidade de dados, e sem exibí-los na URL.

  [video-criando-rota-post](https://watch.screencastify.com/v/GWROCSNf5sVs3j5UItou)
  [video-lidando-com-formulario](https://watch.screencastify.com/v/7XTwqgYGdTOdx8hlr4yh)

## CONFIGURANDO BANCO DE DADOS
  - A configuração do banco de dados acontece dentro do arquivo .env, e toda a criação de tabelas são controladas pelas migrations.
  [video-configurando-banco-de-dados](https://watch.screencastify.com/v/weRMz3N3xfAW5rEVpjDo)

## LINDANDO COM TABELAS, MODELS E MIGRATIONS
  - As tabelas do banco estão vinculadas aos nossos modelos, sendo assim, usaremos os nossos models para fazer todo gerenciamento de dados do banco.
  
  [video-criando-uma-migration](https://watch.screencastify.com/v/atH0gvknrEMlfs6u6HZK)
  [video-inserindo-dados-na-tabela](https://watch.screencastify.com/v/2tlwkXDtNbLOiHMHwh24)
  [video-redirecionamento-e-respostas](https://watch.screencastify.com/v/fsQxTQ3vI7M1rh6TrUJK)
  [video-autenticacao](https://watch.screencastify.com/v/lv3gOhq9oNyIWG0LkibB)
  [video-mostrando-dados](https://watch.screencastify.com/v/PJ7TmgtHGPNE4oBuuhOe)

## REFERENCIAS
[Laravel-Documentation](https://laravel.com/docs/8.x)