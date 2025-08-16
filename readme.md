# 1. Criar pasta e entrar
mkdir meu-repo && cd meu-repo

# 2. Iniciar git e criar arquivo
git init
echo "# Meu Repo" > README.md

# 3. Commit inicial
git add .
git commit -m "first commit"

# 4. Criar repositório no GitHub e já subir
gh repo create meu-repo --public --source=. --remote=origin --push

Para próximas vezes (repos já existentes)

Quando quiser só atualizar o repo depois de mudar arquivos:
```
git add -A
git commit -m "update"
git push
````
