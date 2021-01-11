# Guia de boas práticas de desenvolvimento da Benfeitoria

Abaixo seguem algumas orientações que tem como objetivo garantir minimamente a qualidade de código das aplicações.

## Geral

* Sintaxe em inglês
* Nunca, mas nunca use Hungarian Notation

## CI

* Novas features devem sempre ser acompanhadas de testes unitários e de integração.
* Novas features devem sempre alcançar pelo menos 80% de cobertura de código.
* Novas features devem ser revisadas por outro membro do time de desenvolvimento antes de serem integradas ao próximo release.
* Novas features devem ser criadas em um novo branch e permanecerem no mesmo até o momento de serem incorporadas a algum release.
* Novas features não devem ser incorporadas a um release caso os testes automatizados não sejam executados corretamente.
* Caso um teste unitário seja executado incorretamente, se possível corrija imediatamente ou avise ao autor da mudança que gerou o problema.

## CSS

* [BEM Methodology](http://getbem.com/)
* [BEM Cheat Sheet](https://9elements.com/bem-cheat-sheet/)

## PHP

* [Keep your PHP code well documented](https://www.sitepoint.com/keeping-php-code-well-documented/)
* [PSR-1: Basic Coding Standard](https://www.php-fig.org/psr/psr-1/)
* [PSR-2: Coding Style Guide](https://www.php-fig.org/psr/psr-2/)

### Referências

* [PHP The Right Way](https://phptherightway.com/)
* [PHP Delusions](https://phpdelusions.net/)
* [PHP Design Patterns](https://refactoring.guru/design-patterns/php)

### Laravel

* [Laravel Best Practices](https://github.com/alexeymezenin/laravel-best-practices)

## Git

* [Using git-flow to automate your git branching workflow](https://jeffkreeftmeijer.com/git-flow/)
* [Commit Messages Guide](https://github.com/RomuloOliveira/commit-messages-guide)
