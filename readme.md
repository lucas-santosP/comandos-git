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

### Commit de novos arquivos/modificações

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

### Listar branches

```
git branch --list
```

<hr/>

### Listar mudar de branch

```
git checkout <nome-da-branch>
```

<hr/>

### Merge da branch atual com outra

```
git merge <nome-da-branch>
```

<hr/>

### Status resumido do repositório

```
git status -s
```

<hr/>

## # <b>Outros</b>

### Guardar modificações para commits futuros, stash (esconderijo)

Para guardar modificações no stash

```
git add .<arquivo>
git stash
```

para listar stashs existentes

```
git stash list
```

Para aplicar as modificações guardadas:

```
git stash pop
```

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

## # <b>Configurações</b>

### Abrir configurações globais do git no VS code:

```

git config --global core.editor code
git config --global --edit

```

```

```
