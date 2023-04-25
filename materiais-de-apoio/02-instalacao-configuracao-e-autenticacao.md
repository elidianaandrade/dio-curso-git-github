<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Versionamento de Código com Git e GitHub</span>
</h1>

## Instalação, Configuração e Autenticação	

### Instalando o Git no Windows
- Acesse < https://git-scm.com/download/win >;
- Faça o download do instalador e execute;
- Aceite a licença e clique em “Next”, e siga configurando como desejar¹ e clicando em “Next”;
- Finalize clicando em “Install”, e “Finish”.

¹Em "Select Components“, deixe as opções “Git Bash Here” e “Git GUI Here” marcadas.

##

### Instalando o Git no Linux (Ubuntu)
- Confira a doc.: < https://git-scm.com/download/linux >;
- Instale a última versão estável do Git:
    ```bash
    # add-apt-repository ppa:git-core/ppa
    ```
    ```bash
    # apt update
    ```
    ```bash
    # apt install git
    ```
##

### Instalando o Git no macOS
- Confira a doc.: < https://git-scm.com/download/mac>;
- Instale o Homebrew: < https://brew.sh/ >;
- Instale o Git:
    ```
    $ brew install git
    ```
##

### Configurando o Git
```bash
$ git config --list
```

#### Configurando seu nome de usuário e e-mail (globalmente):
```bash
$ git config --global user.name "Nome Sobrenome"
$ git config --global user.email seuemail@email.com
```
#### Configurando o nome da Branch Padrão:
```bash
$ git config --global init.defaultBranch main
```

##
<div align="center">Feito com 💙 por <a href="https://github.com/elidianaandrade">Eli</a>.</div>
