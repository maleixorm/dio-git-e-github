## 💻 Comandos Git | Dicas Úteis

## Baixar alterações do repositório remoto da branch main

```
git fetch origin main
```

## Mostrar diferenças nos arquivos locais e remotos do repositório

```
git diff main origin/main
```

## Baixar conteúdo da branch remota sem alterar a branch local

```
git merge origin/main
```

## Clonar uma branch específica do repositório

```
git clone (url) --branch (branch-name) --single-branch
```

## Arquivar modificações e mostrar modificações arquivadas

```
git stash
git stash list
```

## Buscar modificações arquivadas e adicionar em outra branch

```
git stash pop
git stash apply
```