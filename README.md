# Git Bash

* Iniciar um repositorio: git init

# Criando um commit
git add nome do aqruivo

## Adiciona todos os arquivos para Stage
git add .

## Verificando os aqruivos que estão em stage esperando ser comitados
git status

## Comitar os arquvivos da sua máquina para o git
git commit -m "nome_da_pasta"

# Renomeando o nome da Branch "Master" para "main"
git branch -M "main"

# Abrindo um repositório do Github no Git bash
git remote add origin https://github.com/julianasmachadodasilva

## Passar os arquivos da sua máquina para o Github
git push -u origin main

# Criando uma feature dentro da Branch main
git checkout -b "nome_da_pasta"
git add .
git commit -m "none_da_pasta"

## Para voltar para a Branch main
git checkout main

## Para voltar para a Branch nome_da_pasta
git checkout nome_da_feature

# Mergeando sua feature na Branch principal
git checkout main
git merge nome_da_feature
git push origin main 





