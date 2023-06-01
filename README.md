# Git configuration commands

```
git config --global user.name "Github Name"
git config --global user.email "Github Email"
```

```
git config --global user.name "Nome do Github"
git config --global user.email "Email do Github"
```

# commands to push the files to the GitHub repository

```
git init
git add (File.exe or --all)
git branch -M main
git commit -m "Your Commit"
git remote add origin "GitHub Repository Link"
git push
```

```
git init
git add (Arquivo.exe ou --all)
git branch -M main
git commit -m "Seu Commit"
git remote add origin "Link do Repositorio do GitHub"
git push
```

# Basic Commands Used

```
git status
git config --list
```

```
git status
git config --list
```

# Mistakes that happened to me and how to fix them

>Error: Repository Unsafe (To set git settings that the directory is safe)

```
git config --global --add safe.directory 'Directory Path'
```

>Erro: Repositório não seguro (Para definir as configurações do git que o diretorio é seguro)

```
git config --global --add safe.directory 'Caminho do Diretorio'
```



>Error: remote origin already exists (To update the existing remote repository)

```
git remote set-url origin 'Directory Path'
```

>Erro: Já existe um repositório remoto (Para atualizar o repositório remoto existente)

```
git remote set-url origin 'Caminho do Diretorio'
```

