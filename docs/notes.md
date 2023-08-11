# Testes automatizados em JavaScript

## Mentiras mais comuns

- É muito demorado criar testes automatizados

  A parte mais demorada de um teste pode ser a configuração do ambiente de teste (banco de dados, mocks)

- Não vale a pena criar testes para uma aplicação que não possui testes

  Primeiro, começar a implementar os testes que são mais demorados de serem realizados. Por exemplo, testar API

- Testes no back-end é fácil, quero ver testar o front-end

  Testes back-end e front-end compartilham das mesmas técnicas de testagem seja API de outro sistema como o navegador, pois o DOM é uma API do browser.

  Por exemplo, em cenários de testagem de componentes React com um alto grau de complexidade, é possível utilizar abordagem como _screenshot_ que consistem em comprar prints para fazer a validação dos layout do site.

- Meu chefe não me deixa testar