Link para download do Git: https://git-scm.com/downloads

# Comandos Git :computer::

## Ajuda

#### Geral 

- git help

##### Comando específico

- git help add

- git help commit

- git help <qualquer_comando_git>

  

## Configuração 

#### Geral 

As configurações do GIT são salvas no arquivo do GIT são as configurações localizadas dentro do arquivo do usuário do Sistema Operacional (Ex.: Windows: C:\Users\Documentos and Settings\ **Useronardo** ou *n /home/leondo).

As configurações apresentadas através dos comandos abaixo incluídos no arquivo citado acima.

#### Definir usuário

- git config --global user.name "Jennifersousa32"

#### Definir e-mail

- git config --global user.email leonardo@software-ltda.com.br

#### Editor Setar

- git config --global core.editor vim

#### Setar ferramenta de mesclagem

- git config --global merge.tool vimdiff

#### Setar arquivos a serem ignorados

- git config --global core.excludesfile ~/.gitignore

#### Listar configurações

- git config --list



## Repositório Local

#### Criar novo recurso

- git init

#### Verificar estado dos arquivos/diretórios

- git status



#### Adicionar arquivo/diretório (área encenada)

##### Adicionar um arquivo em específico

- git add meu_arquivo.txt

##### Adicionar um diretório específico

- git add meu_diretorio

##### Adicionar todos os arquivos/diretórios

- git add .	

##### Adicionar um arquivo que esta lista no .gitignore (geral ou do administrador)

- git add -f arquivo_no_gitignore.txt



#### Comitar arquivo/diretório

##### Comitar um arquivo

- git commit meu_arquivo.txt

##### Comitar vários arquivos

- git commit meu_arquivo.txt meu_outro_arquivo.txt

##### Comitar informando mensagem

- git commit meuarquivo.txt -m "minha mensagem de commit"

  

#### Remover arquivo/diretório

##### Remover arquivo

- git rm meu_arquivo.txt

##### Remover pasta

- git rm -r diretorio