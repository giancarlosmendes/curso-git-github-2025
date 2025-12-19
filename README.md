# Curso TMW Git & GitHub 2025

Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub.

Além disso, vamos trabalhar com GitFlow ao final do curso e Visual Studio Code.

Confira tudo o que temos no YouTube. É gratis!

## Fluxo de trabalho Git local

01. git checkout -b <nova-branch>
02. cria ou atualiza arquivos
03. git status
04. git add <arquivos>
05. git status
06. git commit -m "mensagem"
07. git status
08. git checkout main
09. git merge <nova-branch>

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)

01. git clone <url-do-projeto>
02. git checkout -b <nova-branch>
03. alterações de arquivos
04. git status
05. git add <arquivos>
06. git status
07. git commit -m "mensagem"
08. git status
09. git push origin <nova-branch>
10. abrir Pull request no GitHub para main
11. excluir <nova-branch> do repositório remoto (origin)
12. git checkout main
13. git branch -D <nova-branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)

00. Fork do projeto para seu próprio GitHub
01. git clone <url-do-projeto-fork>
02. git checkout -b <nova-branch>
03. alterações de arquivos
04. git status
05. git add <arquivos>
06. git status
07. git commit -m "mensagem"
08. git status
09. git push origin <nova-branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova-branch> do repositório remoto (origin)
12. git checkout main
13. git branch -D <nova-branch>

------

Pessoas participantes:

- Téo
- Gian