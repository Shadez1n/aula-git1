# comandos git
Neste arquivo será apresentados os comandos git para uso futuro.

## No primeiro uso em um computador 
Para que o GIT avise e saiba quem fez as alterações é necessaário 
configurar o usuário nas configurações globais do git. 
```bash
git config --global user.name "Lui Pantaroto Moschetto"

git config --global user.email "luimoschetto@gmail.com"
```

## Comandos para gestão do Git 
Para inicializar uma pasta com repositório git usamos o comando init.
Só utilizamos este comando 1 vez. 
```bash
git init
```
Para ver a situação do repositório utizamos o comando status.
Ele pode ser executado a qualquer momento para saber a situação da pasta.
Se estiver vermelho precisa adicionar os arquivos, se estiver verde estão prontos
para salva (commit)
Se não aparecer nada, ou o arquivo não está salvo ou já está tudo ok.
```bash
git status
```