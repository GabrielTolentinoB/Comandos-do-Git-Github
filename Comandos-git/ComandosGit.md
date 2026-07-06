---
title: Comandos do Git
description: Comandos do Git de uso diário, para fins de aprendizado
author: Gabriel Tolentino Berloffa
tags: ["git", "github", "mermaid", "branch", "conceitos"]
---

# Comandos GIT

**Iniciando o Git**

```javascript
  git init

  // iniciar um reposiório local

  ou

  git clone URL (Repositório remoto)
  
  // Para clonar de um repositório remoto para sua maquina

```

Após iniciado o GIT, não significa que os arquivos estão automaticamente salvos, como podemos checar com o git status

```javascript
  git status

  // status atuais do git dentro do diretório, se existe arquivos a serem salvos...
  // ...e se estão prontos para Commit
```

```javascript
  git add NomeDoArquivo.ComExtensão

  // Salvando arquivo pro git, agora estando pronto para ser commitados

```

```javascript
  git commit -m "mensagem para commit" - 

  // Commitando e adicionando uma mensagem para o commit, é de suma importancia que...
  // ... todos os commits tenham uma descrição, assim dá para saber o que foi commitado...
  // e é o padrão 
```

```javascript
  git commit --amend -m"mensagem para alterar o ultimo commit"

  //altera a mensagem do ultimo commit
```

```javascript
  git log  

  // histórico de commits, podemos ver todos os commits que já foram gerados, e a...
  // ... descrição, além também do codigo hash do Commit(Ex. de Hash: 5687fds677fsd6...)
```

```javascript
git reset --soft hasg_do_commit - A ser compreendido e editado
```

```javascript
git reset --mixed hasg_do_commit - A ser compreendido e editado

```

```javascript
git reset --hard hasg_do_commit - A ser compreendido e editado

```

```javascript
  git reflog
  // hitorico mais detalhado das alterações -
```

```javascript
  git remote add origin - 
  // conectar 2 diretórios git da maquina ao do GitHub
```

```javascript
  git branch -M main
  // Mudar nome de Master para Main
```

```javascript
  git push -u origin main 
  // push responsável por enviar as alterações do local para o github
```

```javascript
  git remote remove origin 
  // remover um repositório remoto de um diretório
```
## Comandos importantes para o Terminal

```javascript
rm -rf .git - apagar repositório git
```

```javascript
mkdir nome_da_pasta - Criar um diretório
```

```javascript
cd diretório - entrar em um diretório
```

```javascript
touch nome do arquivo - criar um arquivo (bloco de texto extensão .md)
```
asasasa


## Códigos para subir no github no repositório de git

```javascript
Git pull - irá puxar as informações do remoto e colocar dentro do repositório local
```

  :star: Dica: Apertar <kbd>.</kbd> No github abre o vscode online





#
## Coisas sobre branchs (ramificações)

### *criar novo repositório para aprender**

```javascript
  git checkout -b NomeDaBranch - 

  // Irá trocar da branch atual para a branch que está sendo criada
```

```javascript
  git checkout NomeDaBranch
  // Para alterar de branch
```

```javascript
  git branch -v
  // Mostra o último commit de cada branch
```

```javascript
  git branch
  // Mostra as branchs do repositório 
```

```javascript
  git branch -d BranchQueDeveSerExcluida 
  // excluir uma branch
```

```javascript
  git merge NomeDaBranch 
  // indica qual branch deve ser mesclada na branch atual
```



