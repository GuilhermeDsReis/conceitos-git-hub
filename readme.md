# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos para utilização de git e Github.

## Configuração incial
Rode os comandos abaixo no terminal (cmd) do seu computador.
```bash
git config --global user.name "Guilherme Reis"

git config --global user.email guilhermediasreis1@hotmail.com
``` 

## Comandos do Git
Para iniciar o GIT em uma pasta do computador utilizamos o init.
**IMPORTANTE**: Só pode ser executado 1 vez.
``` bash
git init
```
Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no Github e seguir a segunda opção da lisata
de comandos que aparece no site. <br>
**IMPORTANTE:** Depois do remote deve ser executados os outros 2 comandos da página.
``` bash
git remote add origin < url_respositorio_github >
```


Para verificar a situação do repositório (pasta) usamos o status a qualquer momento.
``` bash
git status
```

Quando o status mostrar arquivos em vermelho é necessário rodar o add para adicionar os arquivos a serem salvos.
. adiciona todos os arquivos da pasta atual
``` bash
git add .

```
Para salvar, utiliza-se o 'commit', juntamente com uma mensagem para lembrar o porque salvou as alterações.
``` bash
git commit -m "mensagem do commit"
```