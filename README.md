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

## Primeiro Push
```shell
$ git remote add origin <url>                
$ git push -u origin master #somente a primeira vez
```

## Contribuidores
* Jonata Weber <jonataa@gmail.com>
* Romualdo Andre <romualdoandre@gmail.com>
* Outra Pessoa <outrapessoa@gmail.com>
* Fulano de Tal <fulano@gmail.com>
