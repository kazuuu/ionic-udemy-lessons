Para rodar os apps no ionic, basta ir na pasta dos apps e rodar:<br/ >
  $ ionic serve<br/ >
<br/ >
****************************<br/ >
[Part 1] Single-View App<br/ >
    - my-reddit<br/ >
[Part 2] Multi-view app:<br/ >
    - my-notes<br/ >
[Part 3] Ionic components (Tabs, Sidemenu and Slide box):<br/ >
    - my-tabs<br/ >
    - my-sidemenu<br/ >
    - my-slides<br/ >
[Part 4] AngularJS Concepts (Promises, REST)<br/ >
    - my-promises<br/ >
    - my-notes-json-login<br/ >
    Este app acessa um webAPI para fazer login e gerenciar as notas. O WebAPI esta no app my-notes-auth-backend. Rodar seguindo as instruções dele abaixo.<br/ >
<br/ >
    - my-notes-auth-backend<br/ >
      Para rodar este app precisa rodar o serviço API my-notes-auth-backend, basta executar para instalar:<br/ >
      $ npm install<br/ >
      E rodar com:<br/ >
      $ node server.js<br/ >
      Lembrar que por simular no webbrowser precisa fazer um tweak para permitir as chamadas de links. Utliza a extensao do Chrome:<br/ >
      Allow-Control-Allow-Origin: Allows to you request any site with ajax from any source. Adds to response 'Allow-Control-Allow-Origin: *' header<br/ >
