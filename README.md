# Conhecendo Git e Github - Ajustes de Configuração

Repositório criado para efetuar as entregas de exercícios propostos pela be.academy DevStart.

## Aula de comandos do git

Configurando usuário e email

	git config --global user.name "nome"
	git config --global user.email "contato@email.com"

Cria um repositório e inicia

	git init

Verifica o estado do arquivo

	git status

Adiciona um arquivo

	git add nome-do-arquivo

Adiciona todos os arquivos

	git add .

Remove um arquivo

	git rm nome-do-arquivo

Comita um arquivo com mensagem explicativa

	git commit -m "mensagem-sobre-alteração"

Exibe o histórico

	git log

## Comandos Branch(Ramificações)

Checa em qual branch está e quantos existem

	git branch

Cria um branch

	git branch nome-do-branch

Cria um branch e navega para ele

	git branch -b nome-do-branch

Navega para o branch indicado

	git checkout nome-do-branch

Remove o branch indicado

	git branch -d nome-do-branch

Une um branch indicado ao atual

	git merge nome-do-branch

## Repositório do github no computador

Clona um repositório do github para o computador

	git clone codigo-do-repositório

Mostra os nomes/url dos repositórios remotos

	git remote -v

Altera o endereço url do repositório

	git remote set-url origin new-url

"Empurra" a alteração para o github

	git push
