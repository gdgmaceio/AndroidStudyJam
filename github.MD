
# GitHub primeiros passos
#### [Sign Up - Crie sua conta](Https://github.com/join?source=header-home)

## Basic Commands
#### 1 - Adicionando novo repositorio em um git init
	git remote add origin git@github.com:SEU_USUARIO/NOME_PROJETO.git

#### 2 - Configurando informações sobre o autor dos commits:
    git config --global user.name "SEU_NOME"
    git config --global user.email "SEU_EMAIL"

#### 3 - Criando um repositório local:
    cd meuprojeto
    git init

Para ter certeza que o repositório foi criado:  
    
    git status

#### 4 - Adicionando arquivos novos ou modificados no Stage:

    git add arquivo.txt
    git add *.py
    git add . (para add todos os arquivos)
    git add -i (para modo interativo. 1-5 ou 1,2,3,4 e -3 para retirar)

#### 5 - Commits
Apenas arquivos no Stage podem ser commitados.

    git commit -m "Mensagem"
    git commit -a -m "Mensagem" (commita também os arquivos versionados mesmo nao estando no Stage)

#### 6 - Subindo código para o GitHub
    git push origin master (Envia o que está no branch (master) atual (do seu computador) para o branch (master) no repositório remoto)
    
