<h1 align="center">CadLogin System</h1>
<p align="center">Um sistema de cadastro e login utilizando o padrão MVC.</p>
<br />

## Sobre

Este trabalho avaliativo de PHP da disciplina de Programação Web II envolve o desenvolvimento de um sistema de login e cadastro, com base no padrão MVC de projeto de software.

## Funcionalidade

Este projeto utiliza o padrão MVC. Por isso, ele é separado em Models, Views e Controllers.
As Views são o front-end. Quando o usuário dá um input, essa informação é levada para o Controller, que as transporta para o Model, que processa a informação (back-end). Quando o Model as processa, o output é levado para o Controller e, finalmente, para as Views.

Atualmente, os formulários de cadastro e login estão estilizados, com um script de verificação de credenciais localizado em `controllers/AuthController.php`, que utiliza métodos como (`password_verify()`)[https://www.php.net/manual/pt_BR/function.password-verify.php] e o (Operador de Resolução de Escopo)[https://www.php.net/manual/pt_BR/language.oop5.paamayim-nekudotayim.php].

## Tecnologias Utilizadas

- ✅ PHP
- ✅ HTML
- ✅ CSS
- ✅ Git
