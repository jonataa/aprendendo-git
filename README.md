# Aprendendo o Git
Esse arquivo irá ter todos os comandos do curso de Git.

## Comandos iniciais

```shell
$ git config --global user.name "Jonata Weber"
$ git config --global user.email "jonataa@gmail.com"
$ git init
$ git status
```

## Comandos de Log

```shell
$ git log
$ git log --full-diff -p README.md
```

## Checkout

```shell
$ git checkout -- <file> # Desfaz as mudanças
```

## Trabalhando com Branchs

```shell
$ git checkout -b <name> # Cria e faz checkout na nova branch
# ou
$ git branch <name>      # Cria uma nova branch
$ git checkout <name>    # Alterna entre as branchs
```

## Trabalhando com Tags

```shell
$ git tag                               # lista todas as tags
$ git tag -a v0.0.1 -m 'texto qualquer' # adiciona uma nova tag
$ git show v0.0.1                       # mostra os detalhes da tag
$ git tag -d v0.0.1                     # apaga uma tag
```
