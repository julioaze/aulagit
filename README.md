# GIT E GITHUB

Guia prático

## INSTALAÇÃO

https://git-scm.com/downloads

#### CONTROLAR PONTOS NA LINHA DO TEMPO

[] CRIAR PONTOS NA HISTÓRIA DO PROJETO

# git init

- inicia um repositório, onde o seu projeto ficará guardado

# git add nome_do_arquivo / git add .

- adiciona o(s) arquivo(s) para ser observado pelo Git

# git commit -m "mensagem"

- faz o commit, ou seja, envia o arquivo para o repositório
  # - "criou um ponto na linha do tempo"

[] VERIFIAR MUDANÇAS FEITAS NO PROJETO

# git log

- verifica o "ponto criado na linha do tempo"
- use a tecla 'q' para sair do log

# git status

- verifica o estado dos arquivos no projeto

# Sempre que atualizar um arquivo é necessário usar o comando 'git add' e

# em seguida 'git commit'

- Sempre é possível visitar a linha do tempo com o comando 'git log'

# git show

- exibe o último ponto na história

# git show 'id_do_commit'

- exibe um ponto específico na história

[] INICIAR UMA NOVA FUNCIONALIDADE SEM ESTRAGAR O QUE JÁ ESTÁ FEITO

# git branch nome_branch

- adiciona uma 'ramificação' à linha do tempo principal

# git checkout nome_branch

- entra nessa linha do tempo no universo paralelo :)
- git status para certificar

  - na linha do tempo principal, use git branch para visualizar todos os branchs
  - voltar para o branch alternativo
  - incluir o novo arquivo no monitor do git
  - fazer o commit desse arquivo
  - voltar ao branch master
  - usar o commando 'dir' para listar os arquivos do branch master

[x] ADICIONAR NOVAS FUNCIONALIDADES AO PROJETO EM PRODUÇÃO

# git merge nome_branch

[] APAGAR O BRANCH DA NOVA FUNCIONALIDADE APÓS SER APLICADA NO PROJETO

# git branch -D nome_branch

##### REVISÃO

- 'git init' inicia a linha do tempo
- 'git add' adiciona ou atualiza alterações para a irem para a linha do tempo
- 'git commit' adiciona um ponto na linha do tempo
- 'git log' visualiza os pontos na linha do tempo /commit
- 'git status' informa o estado das alterações do projeto
- 'git show' apresenta um determinado ponto na linha do tempo

[] ENVIAR O PROJETO PARA A NUVEM

# GITHUB :)

- Criar conta no GitHub
- Criar novo repositório
- Copiar os comados sugeridos pelo GitHub

  # git remote -v

  - visualiza os repositórios

  # git push

  - 'empurra' o repositório local para a nuvem

  * use o comando fornecido pelo GitHub para criar a branch master no repositório online
  * nas demais vezes, apenas git push

## DICA

# git config credential.helper store

- grava os dados de login no config
