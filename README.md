# Site-de-vendas
Esse readme foi feito para orientar a como criar um repositório local e repositório remoto(Github).

## Crie ou selecione a sua aplicação
-1 Inicie o git com o comando:
```bash
  git init
```
 Agora o repositório está criado localmente no seu computador, vc pode modificar o seu código mas cuidado nada está salvo completamente.

-2 Veja as mudanças feitas no seu código e os novos arquivos:

  Esse comando mostra as mudanças feitas no arquivo
```bash
  git diff nomedoarquivo
```
  Mostra todos os arquivos do projeto e os que não foram enviados ao stage, mas como não enviamos nada ainda provavelmente nada apareceu indicando arquivos não enviados.
```bash
    git status
```
-3 Fazer o stage:

O stage é basicamente uma área temporaria para poder organizar o seu código, o stage é temporario porque depois de um commit ser feito ele é "limpo". No stage as alterações são add antes de serem confirmadas.

Esse comando adiciona todos os arquivo do projeto que não estão no stage
```bash
    git add.
```
Em casos que vc precisa apenas atualizar um arquivo no stage de forma unitaria use esse comando

```bash
git add nomedoarquivo
```

