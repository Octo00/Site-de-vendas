# Guia para fazer o commit e push para repositorio
Esse readme foi feito para orientar a como criar um repositório local e repositório remoto(Github).

## Crie ou selecione a sua aplicação
### 1. Inicie o git com o comando:
```bash
git init
```
 Agora o repositório está criado localmente no seu computador, vc pode modificar o seu código.

### 2. Veja as mudanças feitas no seu código e os novos arquivos:

  Esse comando mostra as mudanças feitas no arquivo
```bash
git diff nomedoarquivo
```
  Mostra os status gerais do projeto
```bash
git status
```
### 3. Fazer o stage:

O stage é basicamente uma área temporaria para poder organizar o seu código, o stage é temporario porque depois de um commit ser feito ele é "limpo". No stage as alterações são add antes de serem confirmadas.

Esse comando adiciona todos os arquivo do projeto
```bash
git add .
```
Esse comando add um arquivo especifico

```bash
git add nomedoarquivo
```

### 4. Configurar nome de usuario:

Primeiro devemos configurar o nome de usuario e o email antes de fazer o commit pois esses dados serão associados a todos os commits realizados.

Configura o nome de usuario:
```bash
git config --global user.name "nome de usuario"
```

Configura o email:
```bash
git config --global user.email "email"
```

### 5. Realizar o commit

Para realizar o commit é bem simples, mas antes lembre-se de revisar o código antes de fazer o commit. 

Comando para realizar o commit
```bash
git commit -m "descrição do commit"
```
Sempre descreva oq tem no commit ou a modificação feita nele para estar sinalizado oq foi feito.

## Extra!

### 6. Criando o repositorio remoto no github

Após configurar o seu email e nome de usuario, abra o seu navegador(Firefox, Chrome, Brave.Etc) entre no seu perfil do github, abra a aba repositorios e crie um novo deixando o nome e descrição a suas descrições.


### 7. Criar um token privado
No git para fazer um push para um repositório remoto(Github,gitlab,gitness) é preciso de um token unico para realizar o push. Caso vc já tenha o token, ótimo, mas caso não tenha acesse:

Configurações > Configurações de desenvolvedor > Tokens de acesso pessoais > Tokens(Classic)

Lá vc podera configurar o seu token e deixa-lo com os privilégios e funções necessarias para fazer um push e além.

!!!!!!!!!!!!!!!!!!!! Salve esse token!!!!!!!!!!!!!!!!!!!!!!!


### 8. Fazendo o push
Antes de realizar o push, certifique-se de ter configurado o repositório remoto

Esses comandos enviam a versão ao repositório remoto
```bash
git remote add origin https://github.com/seu-usuario/seu-repositorio.git
git push -u origin main
```


## 9. Resuminho 
Fluxo básico do Git

Resumo dos principais comandos utilizados no dia a dia:

```bash
git add .
git commit -m "mensagem"
git push
```

Créditos: Octo00/Wizard cat ⚡🐱⚡

