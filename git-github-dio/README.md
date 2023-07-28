#### Curso disponibilizado pela https://www.dio.me/ de git e GitHub.
#### Link download git: https://git-scm.com/downloads

<br>

# Entendendo o que é git e sua importância.

### git é um sistema de versionamento de código distribuido, criado por Linus Torvalds que também é criador do Sistema Operacional Linux. 

- ## Diferença entre GIT e GITHUB.

### git e GitHub são geralmente associados um ao outro mas são duas coisas totalmente diferente, enquanto o git é responsável pelo versionamento o GitHub é um repositório online de que armazena seu código e arquivos na nuvem e faz controle de versões usando git.

- ## GUI x CLI

### GUI == Interface gráfica do utilizador, ou seja, a interação com o usúario será através de telas gráficas.
### CLI == Interface de linha de comando, ou seja, programa que permite que o usúario dê instruções através de linhas de código para fazer funções específicas.

<br>

# Navegação básica no terminal.

- ## Listagem de pastas.

### dir == Windows
### ls (se executado com a flag -a vai ser listado tudo dentro do diretório inclusive arquivos ocultos) == Linux

- ## Navegar entre diretórios.

### cd / == Base diretório(Windows/Linux)
### cd nome_diretorio = Entra em diretório especificado pelo usuário.
### cd .. == Retrocede um nivel, ou seja, para o último diretório em que o usuário esteve.

- ## Limpar tela 

### (ctrl + L) == Limpar tela (atalho Linux)
### cls == Limpar Tela (windows)
### clear == Limpar tela (Linux)

- ## Criar diretório

### mkdir nome_pasta == cria um diretório, se não aparecer nenhum erro significa que foi criado com sucesso(silence on success).

- ## Apagar 

### del nome_diretorio == Específico para apagar arquivos, não apaga pastas.        
### rmdir nome_diretorio /S /Q == Apaga diretórios com tudo o que estiver dentro. (windows)   
### rm -rf nome_diretorio == Apaga diretórios com tudo o que estiver dentro.   

- ## Atalhos

### (ctrl + L) == Limpar tela (atalho Linux).
### (tab) == auto completar.

# Comandos Git.



- ### git init == A execução desse comando cria um novo subdiretório e cria-se um repositório.
- ### git add == O comando git add adiciona uma alteração no diretório ativo à área de staging. 
- ### git commit == Esse comando vai enviar seus arquivos para o repositório remoto. Use com a flag -m para dar um titulo ao commit.

### No caso de ser a sua primeira vez usando o git, o commit nessecita de ter um autor associado a ele então você precisa setar o seu email e o seu nome, com: 

- #### git config --global user.email "email@provedor.com
- #### git config --global user.name "nome sobrenome" 

#### Imagem exemplificando o funcionamento do git add e git commit => https://www.earthdatascience.org/images/earth-analytics/git-version-control/git-add-commit.png


- ### git clone == clonar um repositório remoto(GitHub por exemplo) para o seu repositório local(sua máquina).
### 




# Comandos Uteis.

### pwd == Mostra o caminho do diretório que você está.
### 
