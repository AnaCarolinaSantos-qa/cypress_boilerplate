# Boilerplate Cypress

Este repositório oferece um ponto de partida para criar testes automatizados com Cypress.

## Recursos

- [Documentação oficial do Cypress](https://docs.cypress.io/guides/getting-started/installing-cypress)
- Cypress definido em `package.json` (faixa compatível: `^13.14.2`)

## Instalação

Para instalar as dependências já definidas neste repositório:

```bash
npm ci
```

Em um projeto novo, inicialize o Node.js com `npm init` e instale o Cypress como dependência de desenvolvimento:

```bash
npm install --save-dev cypress
```

## Estrutura sugerida

```text
cypress/
  fixtures/
    api/
    web/
  support/
    commands.js
    e2e.js
  e2e/
    api/
    web/
cypress.config.js
```

## Executar os testes

```bash
npm run cy:test
```

Para abrir o Cypress em modo interativo:

```bash
npm run cy:open
```

## CI

[![CI](https://github.com/AnaCarolinaSantos-qa/cypress_boilerplate/actions/workflows/ci.yml/badge.svg)](https://github.com/AnaCarolinaSantos-qa/cypress_boilerplate/actions/workflows/ci.yml)

Desenvolvido por [Ana Carolina D. A. dos Santos](https://github.com/AnaCarolinaSantos-qa).
