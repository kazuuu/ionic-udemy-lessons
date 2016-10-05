Para rodar os apps no ionic, basta ir na pasta dos apps e rodar:
  $ ionic serve


****************************
[Part 1] Single-View App
    - my-reddit
[Part 2] Multi-view app:
    - my-notes
[Part 3] Ionic components (Tabs, Sidemenu and Slide box):
    - my-tabs
    - my-sidemenu
    - my-slides
[Part 4] AngularJS Concepts (Promises, REST)
    - my-promises
    - my-notes-json-login
    Este app acessa um webAPI para fazer login e gerenciar as notas. O WebAPI esta no app my-notes-auth-backend. Rodar seguindo as instruções dele abaixo.

    - my-notes-auth-backend
      Para rodar este app precisa rodar o serviço API my-notes-auth-backend, basta executar para instalar:
      $ npm install
      E rodar com:
      $ node server.js
      Lembrar que por simular no webbrowser precisa fazer um tweak para permitir as chamadas de links. Utliza a extensao do Chrome:
      Allow-Control-Allow-Origin: Allows to you request any site with ajax from any source. Adds to response 'Allow-Control-Allow-Origin: *' header
