# Projeto Dio Git/GitHub





## Comandos Básicos de GIT

## Instalando Git
```
sudo apt update
```
```
sudo apt install git-all
```
```
git --version
```


## Configurção Inicial Do Git
```
git config --global user.name "SEU_NOME"
```
```
git config --global user.email "SEU_EMAIL"
```
Para ver o name atual.
```
git config user.name
```
Para ver o email atual.
```
git config user.email
```
Para ver tudo.
```
git config --list
```


## Inicializando um Repositório em um Diretório Existente
```
git init
```


## Clonar Repositório
```
git clone <URL_DO_SEU_PROJETO>
```


## Git status
O comando status do Git fornece algumas informações sobre a branch em que você estiver no momento.
```
git status
```


## Git add
```
git add SEU_ARQUIVO
```
Para adicionar, de uma vez, todos os arquivos modificados.
```
git add .
```


## Git commit
```
git commit -m "MENSAGEM"
```


## Git push
```
git push <REMOTE> <NOME_DO_BRANCH>
```


## Git pull
Usado para obter atualizações do repositório remoto.
```
git pull <remote>
```
## Git branch
Para criar um novo branch.
```
git branch <NOME_DA_BRANCH>
```
Para excluir um branch local.
```
git branch -d <NOME_DA_BRANCH>
```


## Git remote
O comando Git remote estabelece uma conexão entre seu repositório local e um repositório remoto.
```
git remote add <NOMECURTO> <URL>
```
```
git remote -v
```
