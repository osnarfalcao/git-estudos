# ESTUDOS DE GIT

## O que é git?

## Para que serve?

## Comandos mais utilizados:

#### Inicializa um novo projeto git

```
git init
```

#### Verifica o status do projeto
```
git status
```

#### Adicionando arquivos ao stage
```
git add nome-arquivo.txt
git add .
git add *.txt

```

#### Registrando mudanca com commit
```
git commit -m "mensagem"
git commit -am "mensagem"
```

#### Verifica mudanca entre os arquivos
```
git diff 
```


#### Exibir quem fez a mudanca 
```
git log 
```


#### Seta qual endereco remoto ira subir
```
git remote add nome-remote url-remote 

git remote add origin git@github.com:osnarfalcao/git-estudos.git

```

#### Lista os remotes
```
git remote -v

```

#### Envia as mudancas para o repositorio remoto
```
git push 

git push nome-remote nome-branch

git push origin master

```

#### Puxa as mudancas que estao no repositorio remoto
```
git pull

git pull nome-remote nome-branch

git pull origin master

```

#### Criando a chave

ssh-keygen -t ed25519 -C "osnarfalcao@gmail.com"

# Autor
Osnar falcao

# Referencias

https://blog.cedrotech.com/git-o-minimo-que-voce-precisa-saber-para-trabalhar-em-equipe-parte-2

# ---------- 
- estudar e documenta sobre linux da mesma forma do windows
- atualizar meu linkedin: criterio, descricao, quem sou eu, oq estou estudando, oq eu qro pro futuro.
- posta no linkedin o que eu apreendi.
