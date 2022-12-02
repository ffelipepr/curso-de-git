# Meu curso de GIT

## Inicializando um repositório rapidamente

1 - Crie um novo repositório no github

2 - Crie uma pasta vazia (com o nome do projeto)

3 - Crie um arquivo utilizando o comando abaixo
```bash
   $ echo "# Meu curso de GIT" >> README.md
```

4 - Inicialize o repositório utilizando:
```bash
   $ git init
```

5 - Adicione o arquivo README.md para ser "visto" pelo git.
git add README.md
git commit -m "first commit"
git branch -M main

git remote add origin https://github.com/ffelipepr/curso-de-git.git
git push -u origin main
