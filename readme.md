# GIT

## Acessar 
>git-scm.com

## Realizar download do GIT, v.2.43.0

## Instalar o GIT, seguindo o padrão do instalador (Next-Next)

## Verificar versão instalada
> git -v 
>
    git version 2.43.0.windows.1

## Criar ou escolher um diretório para configurar o repositório do git
> mkdir projeto

## Acesse o diretório
> cd projeto

## Inicializar o armazenamento em repositório git
> git init 
>
    Initialized empty Git repository in projeto/.git/

## Configurar os dados do usuário
> git config --local user.name "Usuario"

> git config --local user.email "usuario@dominio.com"

## Verificar mudanças
> git status

## Preparar as mudanças para serem salvas
#### Para preparar apenas um arquivo
> git add file
#### Para preparar todos os arquivos (quando queremos todos os arquivos)
> git add .

## Salvar as mudanças (commit)
> git commit -m "Mensagem do Commit"
>  
    O parametro "-m" define que estamos informando uma mensagem referente aos códigos que estamos salvando.

## Deslogar GIT do terminal
>git config --global --unset user.name

>git config --global --unset user.email

>git config --global --unset credential.helper

## Clonar um projeto (Baixar projeto)
> git clone https://github.com/usuario/projeto.git
>
    "usuario" nome do usúario git;
    "projeto" projeto que será baixado.

## Acesse o diretorio do projeto clonado
> cd projeto

## Para vizualizar no editor vscode
> code .

## Salvar uma modificação
Para identificar as mudanças:
> git status

Para preparar as mudanças para salvar:
> git add .

Salvar as mudanças:
> git commit -m "Mensagem"

## Enviar para o servidor online
>git push -u origin master

## Mostrar o GIT
>git show
