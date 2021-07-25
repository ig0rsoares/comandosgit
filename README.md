# comandosgit
## Lista de comandos utilizados com frequência no git
Iniciar o git para uma pasta ja existente localmente:
```
git init
```
Exibe o status do git, se existe algum arquivo para commitar em qual branch está, etc(verde ok | vermelho pendente):
```
git status
```
Exibe informações e configurações do repositorio:
```
git config -l
```
Realizar configurações de nome de usuário e email ao git de forma global:
```
git config --global user.email igor_soares15@live.com
git config --global user.name ig0rsoares
```
Adicionar um repositório remoto ao seu projeto:
```
git remote add origin https://github.com/ig0rsoares/aulaphp.git
```
Cria uma nova branch (ramificação):
```
git branch nomedabrach
```
Muda para uma branch especifica - utilizada quando nao se quer afetar a main branch:
```
git checkout nomedabranch
```
Clona o repositorio do projeto para o diretorio local:
```
git clone url-repositorio
```

Adiciona todos os arquivos modificados para serem commitados:
```
git add .
```
Comita as alterações feitas nos arquivos localmente:
```
git commmit -m "mensagem do commit"
```
Receber as modificações do repositorio remoto: (DAR GIT PULL ANTES DO GIT PUSH !!!)
```
git pull
```
Sobe os comittis para o repositorio remoto:
```
git push 
```

