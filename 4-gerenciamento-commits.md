# GERENCIAMENTO DE COMMITS
> Comandos para gerenciar os commits.

## Adicionando pastas, subpastas e arquivos ao repositório.
$ git add .

## Comando para commit rápido com parametros -a -m que fará ADD e incluirá mensagem e um alinha de comando apenas:
$ git commit -a -m "Incluido instrução de commit rapido."

## Verificar todos os commits executados:
$ git log
> (HEAD -> main) é o ponto que estamos trabalhando.

## Verificar os logs de um arquivo expecífico:
$ git log -p <nome arquivo>

## Voltar a um commit específico:
# Pegar o hash pelo comando "git log".
$ git checkout <hash do commit a retornar>

## Voltar a posição recente:
$ git checkout main

## Remover o ultimo COMMIT e mantém as alterações do arquivo para você rever:
$ git reset --soft HEAD~1

## Remover ultimo COMMIT e retornando o estado do arquivo para o último COMMIT:
$ git reset -- hard








