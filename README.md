# Git e GitHub - Hashtag



- Config inicial

> Iniciar git
```bash
git init
```  

> Identificação
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```


- Diretórios e arquivos

> Navegar entre diretórios
```bash
cd
../
```

> Listar diretórios e arquivos
```bash
ls
```

> Criar diretório
```bash
mkdir diretorio_name
```

> Remover diretório
```bash
rm -rf pasta/
```

> Criar arquivo
```bash
touch arquivo_name.txt
```

> Remover arquivo
```bash
rm arquivo_name
```

- Branches

> Visualizar lista de branchs
```bash
git branch
```

> Criar branch
```bash
git switch -c branch_name
```

> Alterar branch
```bash
git switch branch_name
```

> Mesclar branch
```bash
git merge branch_name
```

- Alterações

> Enviar modificação para staging area 
```bash
git add .
git add arquivo.js
```

> Salvar modificação
```bash
git commit -m "mensagem"
```

> Verificar satus da modificação
```bash
git status
```

> Verificar log das modificações
```bash
git log
```


- Repositórios

> Clonar
```bash
git clone URL
cd projeto/
```

> Verificar modificações
```bash
git remote -v
```

> Enviar modificações
```bash
git push origin main
```

> Receber modificações
```bash
git pull origin branch_name
git fetch
```

> Git Stash
```bash
git stash
git stash pop
```

> Desfazer modificações (Reset Soft)
```bash
git reset --soft HEAD~1
```

> Desfazer modificações (Reset Hard)
```bash
git reset --hard HEAD~1
```

> Desfazer modificações (Revert)
```bash
git git revert ID_COMMIT
```

> Gitignore
```bash
node_modules/
.env
*.log
```

- Comandos gerais

> Como verificar a versão do Git
```bash
git --version
```

> Verificar configurações setadas
```bash
git config --list
```

teste3
