# dio-desafio-github

## Principais comandos GIT
#### Para inicializar um repositório:
- **git init**

    Para inicializar um repositório

- **git status**

    Para obter informações atuais do repositório

- **git add . ou git add [nome-do-arquivo]**
    
    Adiciona os arquivos modificados para fazer o commit

- **git commit -m "[mensagem]"**

    Commita os arquivos adicionados

- **git commit --amend**

    Altera um commit existente no repositorio local que ainda não tenha sido publicado no github

- **git clone**

    Clona um repositorio existente no github

- **git push**
- **git push origin [nome-do-branch]**

    Publica as alterações, commits em um servidor (repositório) remoto

- **git pull**
- **git pull origin [nome-do-branch]**

    Atualiza o repositório local conforme o repositório remoto

#### Branchs
- **git branch**

    Lista os branchs existentes

- **git checkout [nome-do-branch]**

    Troca, alterna ou seleciona um branch

- **git branch [nome-do-branch]**
    
    Cria um branch

- **git branch -d [nome-do-branch]**
    
    Deleta um branch local

- **git push [nome-remoto] :nome_do_branch**

    Deleta um branch remoto


#### Merge
- **git merge [nome-do-branch]**

    Fazer um merge. Juntar as alterações de um determinado branch  com o branch principal, master. 
    
    Também está relacionada à resolução de conflitos, é necessária quando o git não consegue identificar quem realizou uma alteração num determinado arquivo.