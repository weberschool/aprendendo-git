# Aprendendo Git
Esse arquivo faz parte do meu primeiro repositório usando a ferramenta Git.

## Meu primeiro commit

```shell
$ touch README.md
$ git add .
$ git commit -m "Meu primeiro commit"
$ git log --full-diff -p .
```

## Criando Branchs

```shell
$ git checkout -b <name>
# ou
$ git branch <name>
$ git checkout <name>
```

## Excluindo Branchs

```shell
$ git branch -d <branch-name>
```

## Repositório Remoto

```shell
$ git remote add origin <url>
$ git push origin
$ git pull
$ git fetch
```

## git-log
```shell
$ git log --oneline --graph --decorate --all
```

## Contribuidores
* Jonata Weber <jonataa@gmail.com>
* Romualdo Andre <romualdoandre@gmail.com>
* Outra Pessoa <outrapessoa@gmail.com>
* Fulano de Tal <fulano@gmail.com>
