# Aprendendo Git
Esse arquivo faz parte do meu primeiro repositório usando a ferramenta Git.

## Meu primeiro commit

```shell
$ touch README.md
$ git add .
$ git commit -m "Meu primeiro commit"
$ git log --full-diff -p .
```

## Manipulando Branchs

```shell
$ git checkout -b <name>
$ git branch -d <branch-name>
$ git checkout -b <branch-name> origin/<branch-name>
$ git checkout --track origin/<branch-name>
```

## Repositório Remoto

```shell
$ git remote add origin <url>
$ git push origin
$ git pull
$ git fetch
```

## Comandos de log

```shell
$ git log
$ git log --full-diff -p README.md
$ git log --oneline --graph --decorate --all
```

## Primeiro Push
```shell
$ git remote add origin <url>                
$ git push -u origin master #somente a primeira vez
```

## Trabalhando com tags

```shell
$ git tag #lista as tags
$ git tag -a <tag> -m <message> #adiciona uma nova tag
$ git tag -d <tag>  #apaga a tag
$ git show <tag> #mostra o log da tag
```
## Contribuidores
* Jonata Weber <jonataa@gmail.com>
* Romualdo Andre <romualdoandre@gmail.com>
* Outra Pessoa <outrapessoa@gmail.com>
* Fulano de Tal <fulano@gmail.com>
