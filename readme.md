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

#GIT PUSH (envia os arquivos)
> git push -u origin main


#Commitar todos os arquivos
> git commit -am "mensagem"


#subir atualizações

#Conteúdo Teste

Primeira mudança

www.mbiasotto.com



- Colocando um erro pra teste




Testando o Git DIFF