<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Versionamento de Código com Git e GitHub</span>
</h1>

## Primeiros Passos com Git e GitHub

### Criando e Clonando Repositórios
Existem duas formas de obter um repositório Git na sua máquina:
1. Transformando um diretório local que não está sob controle de versão, num repositório Git;
2. Clonando um repositório Git existente.

#### Criando um Repositório Local
Acesse a pasta que deseja transformar em um repositório Git  pelo terminal ou clique no atalho em “Git Bash Here”:
1. Inicialize um repositório Git no diretório escolhido:
    ```bash
    $ git init
    ```
2. Conecte o repositório local com o repositório remoto:
    ```bash
    $ git remote add origin https://github.com/username/nome-do-repositorio.git
    ```
##

### Desfazendo Alterações no Repositório Local

#### Como alterar a mensagem do último commit
```bash
$ git commit --amend
```
Alterando a mensagem sem abrir o editor:  
```bash
$ git commit --amend –m"nova mensagem"
```

#### Como desfazer um commit
```bash
$ git reset
```
```bash
$ git reset --soft
```
```bash
$ git reset --mixed
```
```bash
$ git reset --hard
```

### Enviando as alterações do repositório local para o repositório remoto

Após fazer suas alterações locais e confirmá-las com os commits apropriados, você pode enviá-las para o repositório remoto no GitHub. Aqui está o procedimento básico para fazer isso:

1. Verifique o status dos seus arquivos:
    
    ```bash
    $ git status
    ```

2. Adicione os arquivos que você deseja enviar:

    ```bash
    $ git add .
    ```

    Ou você pode adicionar arquivos específicos com:

    ```bash
    $ git add nome-do-arquivo
    ```

3. Confirme as alterações:

    ```bash
    $ git commit -m "Descrição das alterações feitas"
    ```

4. Envie as alterações para o repositório remoto:

    ```bash
    $ git push origin master
    ```

**Nota:** Se você estiver trabalhando em uma branch diferente de **'master'**, substitua **'master'** pelo nome da branch em que você está trabalhando.

E é isso! Seu código agora deve estar atualizado no GitHub. Lembre-se de sempre puxar as atualizações do repositório remoto antes de fazer alterações locais para evitar conflitos.

##
<div align="center">Feito com 💙 por <a href="https://github.com/elidianaandrade">Eli</a>.</div>
