# Comandos úteis GIT

## # <b>Essenciais</b>

### Iniciando repositório local

```
git init
```

### Adicionando repositório remoto

```
git remote add origin <url-remote>
git push -u origin master
```

<hr/>

### Adicionando e commitando arquivos

```
git add .<arquivo> && git commit -m <nome-do-commit>
```

atalho

```
git cm <nome-do-commit>
```

<hr/>

### Push pra branch atual

```
git push origin HEAD
```

atalho

```
git psh
```

<hr/><hr/>

### Desfazer todos arquivos adicionados no git add

```
git reset
```

<hr/><hr/>

### Adicionando novos arquivos num commit já existente

```
git add .<novo-arquivo>
git commit --amend --no-edit
```

<hr/>

### Status resumido do repositório (git status -s)

```
git st
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

# Configurações

#### Abrir configurações globais do git no VS code:

```
git config --global core.editor code
git config --global --edit
```
