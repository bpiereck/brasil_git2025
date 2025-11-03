# Dicionário de conceitos

- Git: Ferramenta que apresenta uma linha tempo com todas as modificações. Software de controle de versões. 

- Github: Plataforma para guardar os respositórios e colaborar com outras pessoas. Funciona como backup da linha do tempo.

# Rotina basica de criação de um ponto na linha do tempo

git add <arquivo>

git commit -m <mensagem>

- Qual a importância da mensagem: 

Deixar o usuário e seus colaboradores cientes das atualizações do arquivo.
Questões relevantes para considerar na minha mensagem

- Por quê
- Como
- Limitações
- Efeitos

## Areas conceituais

- Area de desenvolvimento: Onde os arquivos do projeto são editados no seu computador. A pasta onde estão os arquivos do projeto.

- Area de __Staging__ : Aread e preparo para triagem do que será enviado ao git. 

- Repositório local: Local onde vão os commites, as versões dos meus arquivos, versões do meu projeto. Este é encontrado como forma de arquivo na pasta .git que dever ser protegida com a minha propria vida.

## Quando usar git status e o como entender os resultados

Explicação:

Para ter uma idea da organização geral do arquivos.

Verificar se a versão mais atual está salva.

Verificar o status dos arquivos no repositorio.

Verificar pendencias.


Resultados:

1. Changes to be committed (mudanças a serem submetidas):

Quer dizer que o arquivo encontra-se na area __staging__ . O que significa que eu já fiz `git add nome_do_Arquivo.md`

2. Untracked files (arquivos não monitorados):

Arquivo novo, sem nenhuma versão salva. 

3. Changes not staged for commit:

Arquivo com mudanças que não foram enviadas para o __staging__. O que significa que eu preciso terminar todo a rotina básica do git

`git add nome_do_arquivo.md` seguido de `git commit -m "mensagem"`