# Configuração do Git

## Primeiros passos:
### No terminal digite os comandos:

* git config  --global user.name -> para criar um usuário
* git config --global user.email m (email do usuário) -> registrando o email

### Clonando o repositório:

* git clone +url tirado do github code 

### Criando um arquivo git para poder versionar:

* git init -> inicia uma pasta para torna-la pasta git

### Consultando o Status do arquivo:

*git status -> diz status do arquivo

### Atualizando o arquivo em Staged:

* git add (arquivo) ou git add * -> para atualizar tudo

### Commit do arquivo:

* git commit -m ("mensagem")

### Comando para ver as alterações realizadas:

* git diff -> mostra as alterações sofridas no código

### Mostrar o histórico do commit:

* git log -> mostra historico dos commit

### Retornado as alterações:

* git restore(nome do arquivo) -> restaura o ultimo commit
* git restore --staged (nome arquivo) -> para mostrar onde queremos voltar 

### Subindo o arquivo para github:

* git push origin main -> enviando repositório

### Atulizando o arquivo que vem do repositório remoto:

* git pull -> baixa as atualização dos arquivos

### Verificar alterações no arquivo remoto:

* git fetch -> mostrar a diferenças do código remoto para local

### criando ramificações:

* git branch 'nome' -> criando uma ramificação
* git log --oneline --decorate -> mostra onde esta a Head ou ponterio onde esta usando a branch
* git checkout 'nome' -> mudando o Head de lugar para nova branch

### Criando arquivo para ignorar certos arquivos:

* Crie o arquivo .gitignore -> serve para git ignorar arquivos

### juntando arquivos de várias branch:

* git merge (nome arquivo) -> uni os branch 


### Termos usados no git:

* Unmodified -> esse arquivo foi salvo  as modificações no git
* Modified -> arquivo foi modificado saindo do Unmodified  e entrando no estado Modified
* Staged -> area que passa para commit
