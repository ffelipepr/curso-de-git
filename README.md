# ![Dog](https://pipz.com/static/images/blog/eddie.png) Meu curso de GIT ![Dog](https://pipz.com/static/images/blog/eddie.png)

## Adicionando uma mudança apenas no repositório remoto

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

5 - Adicione o arquivo README.md para ser "visto" pelo git usando o comando 'add':
```bash
    $ git add README.md
```

6 - Faça o primeiro commit para gravar as mudanças:
```bash
    $ git commit -m "first commit"
```

7 - Crie a branch principal usando o comando abaixo:
```bash
    $ git branch -M main
```

8 - Adicione a origem do repositório remoto:
```bash
    $ git remote add origin https://github.com/ffelipepr/curso-de-git.git
```

9 - Sincronize o conteúdo da branch main local com o servidor remoto (Github)
```bash
    $ git push -u origin main
```

Aiaiaiaiaia
