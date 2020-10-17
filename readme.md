# Comandos úteis GIT

## # <b>Essenciais</b>

### Iniciando repositório local

```
git init
```

### Adicionando um repositório remoto

```
git remote add origin <url-remote>
git push -u origin master
```

<hr/>

### Commit de novas modificações

```
git add .<caminho-dos-arquivos>
git commit -m <nome-do-commit>
```

<hr/>

### Enviando modificações para branch atual

```
git push origin HEAD
```

<hr/>

### Desfazer todos arquivos adicionados no git add

```
git reset
```

<hr/>

### Adicionando novos arquivos no ultimo commit existente

```
git add .<caminho-dos-arquivos>
git commit --amend --no-edit
```

<hr/>

### Status resumido do repositório

```
git status -s
```

<hr/><hr/>

## # <b>Branches</b>

### Criando uma nova branch

```
git checkout -b <nome-da-branch>
git push -u origin <nome-da-branch>
```

### Excluindo uma branch

```
git branch -D <nome-da-branch> // local
```

```
git push origin --delete <nome-da-branch> // remote
```

### Listando todas as branches

```
git branch
```

<hr/>

### Mudar de branch

Para quando a staging area esta limpa

```
git checkout <nome-da-branch> 
```

Para quando existe modificações na staging area, fará merge das modificações no novo branch

```
git switch -m <nome-da-branch> //
```
<hr/>

### Merge da branch atual com outra

```
git merge <nome-da-branch>
```

<hr/><hr/>

## # <b>Atalhos</b>

```
git push origin HEAD
-
git psh
```

```
git add --all && git commit -m <nome-do-commit>
-
git cm <nome-do-commit>
```

```
git status -s
-
git st
```

## # <b>Outros</b>

### Guardar modificações para commits futuros, stash (esconderijo)

Para guardar modificações no stash

```
git add .<arquivo>
git stash
```

para listar stashes existentes

```
git stash list
```

Para aplicar as modificações guardadas:

```
git stash pop
```

### Abrir configurações globais do git no VS code:

```
git config --global core.editor code
git config --global --edit
```
