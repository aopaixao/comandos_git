# Lista de comandos GIT

```bash
## Iniciando um novo projeto local a partir de um repositório vazio existente no GIT

git init
git remote add origin git@github.com:<YOUR_REPOSITORY_ADDRESS>
git add .
git commit -m "Primeiro Commit" 
git branch -M main
git push -u origin main
```

### Explicação de cada passo
1. Inicialização/criação de um novo repositório git (estando na pasta local do projeto)
2. Adicionando/setando o repositório remoto
3. Adicionando os arquivos a serem versionados (com o '.', todos os arquivos e pastas serão versionados, exceto os constantes no .gitignore)
4. Criando o commit
5. Renomeando a branch local para "main"
6. Subindo os arquivos para o repositório remoto


## Sobre

- Author - [Alexandre Paixão]

## Licença

GNU GPL

