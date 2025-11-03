# Lista de comandos

## Como initicializar o repositorio git

git init

## Verificar e modificar configurações do git

- verificar

git config --global --list

- Modificar

git config --global user.name "MeuNome"

git config --global user.email "meu@email.com"

## Rotina básica do git

Save

git status (conferir em qual area concentual meu arquivo está)

git add <arquivo> (adicionar na __staging__ area )

git commit -m "mensagem relevante" (enviar para o repositorio local)

## Rotina não tão básica do git com github

1. Situação: Atualiazei meus arquivos no repositorio local e fiz o backup no github

   salvei

   git add arquivo.md

   git commit -m "linda mensagem"

   git push 

2. Situação:

   a. Eu atualizei meus arquivos no github e quero sync com o repositorio local

   b. Meu colaborador atualizou o arquivo e eu quero sync no meu repositorio local

   git pull

3. Situação: O mundo ideal

   git pull

   editar os arquivos

   git status

   git add arquivo.md

   git commit -m "linda mensagem"

   git push
