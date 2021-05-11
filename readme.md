#Primeiro Git
>GIT INIT

> git status

#1 colocar na stage

> git add nomedoarquivo.php

#2 Commite

#git commit -m "Criado o Readme.md"

#3 Logs git
> git Log

> git log --decorate

> git log --author="Nome"

> git shortlog
>> bom para ver quem contribuiu, pois lista todos os autores

> git shortlog -sn
>> Mostra a quantidade de commit de cada user

> git log --graph

> git show 321123412122 (hash)

> git diff
>> Mostra o que será gravado / o que foi modiicado

> git diff --name-only
>> mostra só os nomes dos arquivos que foram editados


#DESFAZER / RESETAR  
> git checkout nomedoarquivo.php

> git reset HEAD nomedoarquivo.php
>> Tira da fila do stage

#Resets (para retornar arquivos que já estão comitados ou no stage)
> git reset --soft    OU     --mixed    OU     --hard   + HASH
>> soft: vai matar o commit mas vai ficar na stage
>> mixed: vai matar o commit e volta antes do stage
>> hard: vai matar tudo que foi feito no commit e volta no inicio mesmo
>> ** usar a HASH anterior



##SSH
ssh-keygen -t ed25519 -C "mauricio@mbiasotto.com"

Gerar chave>
https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent


#GIT REMOTE
> git remote add origin https://github.com/mbiasotto/git-curso.git  (pega no repositorio)
> git remote
> git remote -v

#GIT branch
> git branch -M main
> git branch (lista os branchs) (* é o que vc está no momento)
> git checkout nomedobranch (pra trocar entre os branchs)
> git branch -D nomedobranch (deleta)

#GIT PUSH (envia os arquivos)
> git push -u origin main


#GIT CLONE (copiar arquivos)
git clone    + Link +    nome da posta
git clone https://github.com/joetorres/sensor-altura.back.git sensor


#Commitar todos os arquivos
> git commit -am "mensagem"



#FORK (copia, faz as alterações e depois envia para a pessoa aprovar)


#GIT IGNORE
*.json (ignoraria todos os json)


#GIT STASH
> git stash
> git stash apply
> git stash list
> git stash clear

# GIT ALIAS
> git config --global alias.s status
> git config --global alias.c commit
> alias.+leta = comando

#VERSÔES do SISTEMA / etapa
#GIT TAG
> git tag - + versão
> git tag -a 1.0.0 -m "status do projeto"

> git push origin master --tags

#GIT REVERT
> git revert + hash


#DELETAR TAGS e BRANCS remoto
> git push origin :1.0.0 (+:versão)



#subir atualizações

#Conteúdo Teste

Primeira mudança

www.mbiasotto.com



- Colocando um erro pra teste




Testando o Git DIFF