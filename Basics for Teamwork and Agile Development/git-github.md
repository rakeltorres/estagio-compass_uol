# GIT
O Git é um sistema de controle de revisão rápido, escalável e distribuído, com um conjunto de comandos excepcionalmente rico que fornece operações de alto nível e acesso total aos componentes internos.


Explicação e falar sobre o modo work-stage-commit

## Comandos básicos

|  Comando  |    Descrição    | Observações |
| :-------: | :-------------: | :---------: |
| `git config --global user.name/user.email <nome/email>` | configuração do seu espaço git| --global, user.name, user.email|
| `git init` | iniciar um novo projeto | -- |
| `git add ./<nome-do-arquivo>` | adiciona os arquivos no modo stage | pode adicionar todos os files "." ou adicionar um file específico|
| `git commit -m "mensagem-do-commit"` | adiciona os arquivos para o modo commit | o "-m" permite que adicionemos mensagem ao commit feito |
| `git status` | Mostra como está o estado da nossa ramificação |
| `git restore ./<nome-do-arquivo>` | i | pode descartar todas as mudanças dos files "." ou descartar as mudanças feitas em um file específico | 
| `git log` | mostra os últimos commit, log de alterações |
| `git diff` | mostra o que foi alterado e o que tem de alteração na ramificação |
| `git branch` | mostra a branch atual |
| `git checkout -b <nome-da-branch>` | cria uma nova branch a partir da branch atual que estamso |
| `git checkout <nome-da-branch>` | muda para a branch indicada  |
| `git reset` | iniciar o git no terminal |
| `git merge <nome-da-branch>` | mescla ramificações |


# GitHub
Explicação

## Comandos básicos para GitHub


| Comando    | Descrição                 |
| :--------: | :-----------------------: |
| `git remote add <nome> <url>` | adiciona um novo repesitório remoto |
| `git push <nome> <nome-da-branch>` | manda as alterações locais para o repositório remoto, para cada branch |
| `git pull <nome> <nome-da-branch>` | pega as alterações do repositório remoto e trás para nossa máquina |
| `git fech` | atualiza o novo histórico local de acordo com o histórico salvo no repositório remoto (faz uma sincronização do local com o remoto) |
| `git clone` |  |
