# Testes Automatizados utilizando o Github Actions

## Objetivo
O objetivo deste repositório é realizar testes automatizados com Github Actions, ferramenta muito utilizada dentro da esteira de Implantação Contínua (CI) garantindo que os testes rodem sob uma ação pré determinada.

## Como funciona?
Subimos o nosso código com testes desenvolvidos com Jest para uma nova branch criada (my-new-branch). Em nossos arquivos, teremos um arquivo .yml para configurar nossos steps de automatização. A ideia é que todas as vezes que fizermos um Pull Request para a branch Main, os nossos testes sejam executados.

## Tecnologias Utilizadas

- Javascript
- Jest
