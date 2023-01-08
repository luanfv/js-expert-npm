# Gerenciamento de pacotes NPM

Antes de qualquer coisa, é necessário fazer login no npm pelo terminal
```bash
$ npm login
```

## Publicando projeto no NPM

1. Altere o `name` do pacote em package.json para `@{SEU_USERNAME_NO_NPM}/{NOME_DO_SEU_PACOTE}`
0. Execute o script abaixo dentro da raiz do projeto
```bash
$ npm publish --access=public
```

## Publicando nova versão do projeto no NPM

1. Acrescente a versão em `version` do pacote em package.json
0. Execute o script abaixo dentro da raiz do projeto
```bash
$ npm publish --access=public
```