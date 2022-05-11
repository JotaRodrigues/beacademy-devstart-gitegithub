# Conhecendo Git e Github - Ajustes de Configuração

Repositório criado para efetuar as entregas de exercícios propostos pela be.academy DevStart.

## Aula de comandos do git

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

