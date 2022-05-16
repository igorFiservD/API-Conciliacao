# Controle de API-Conciliacao

## Baixar e instalar dependências
link [git download](https://gitforwindows.org/), para instalar só dar next next.
link [vsCode](https://code.visualstudio.com/download), para instalar só dar next next.

## Criar pasta do Projeto
```jsx
$ cd c:
```

```jsx
$ mkdir Projetos
```
		
## clone do projeto
-navegar ate a pasta do projeto.
```jsx
$ cd c:/Projetos
```
-clonar projeto.
```jsx
$ git clone https://github.com/igorFiservD/API-Conciliacao.git
```
		
## Iniciar vsCode
```jsx
$ code c:/Projetos/API-Conciliacao
```

## Configurar acesso dentro da pasta do projeto
-configurar username.
```jsx
$ git config --global user.name "nome sobrenome"
```
-configurar email.
```jsx
$ git config --global user.email "meuemail@github.com"
```

## Principais comandos
-adcionar somente arquivo modificado.
```jsx
$ git add "nome-do-arquivo-novo"
```
-comando para commitar.
```jsx
$ git commit -m "mensagem de aviso do que esta sendo atualizado"
```

-usando plugin do vsCode.
-caso seja um txt ou outras extenções. dê um ctrl-s para salvar, ao lado esquerdo tem o icone para commitar algo, clica, aparecera um campo para inserir a msg de commit, depois empurra commit.

### puxar repositório.
-antes de realizar qualquer modificação diária, atualizar seu projeto com o seguinte comando.
```jsx
$ git pull
```

### empurrar repositório
-adcionar todas as modificações.
```jsx
$ git add .
```
-empurrar todas modificações  .
```jsx 
$ git push
```
