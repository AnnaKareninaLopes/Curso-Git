# Curso Git e GitHub

Aprendendo Git e GitHub.

Com o curso:
[Git e Github para iniciantes](https://www.udemy.com/course/git-e-github-para-iniciantes)

Git para iniciantes

OBS: Usando o windows

1. Criei o arquivo no pycharm
2. No terminal

    2.1. git init
   
    2.2. Get-ChildItem -Force (ver os arquivos na pasta)
   
    2.3. Para conferir...
        
        2.3.1. cd .git (entra na pasta)
        
        2.3.2. Get-ChildItem -Force
        
        2.3.3. cd .. (volta para a pasta anterior)
   
    2.4. echo "# Nome" > README.md (cria o arquivo)
   
    2.5. git status
        
        2.5.1. untracked - Arquivos que foram criados ou adicionados ao diretório, mas que ainda não foram adicionados ao controle de versão (Git). O Git não os rastreia até que sejam explicitamente adicionados com git add.
        
        2.5.2. unmodified - Arquivos que estão no repositório e que não foram alterados desde o último commit. Não há mudanças para adicionar ou commitar.
        
        2.5.3. modified - Arquivos que foram alterados desde o último commit, mas que ainda não foram adicionados ao stage. Eles são reconhecidos pelo Git como modificados, mas não serão incluídos no próximo commit a menos que sejam adicionados ao stage.

        2.5.4. staged - Arquivos que foram modificados e depois adicionados ao stage com git add. Esses arquivos estão prontos para serem incluídos no próximo commit.

    2.6. git add README.md (está no staged)

    2.7. git commit -m "comentário"

    2.8. 3 passos mostrados no próprio site github

        2.8.1. git remote add origin ...

        2.8.2. git branch -M main

        2.8.3. git push -u origin main

    * Modificações
    
    2.9. git commit -am "comentário"

    2.10. git push origin main

3.  Branch: Ponteiro móvel que leva a um commit. Pode criar outras além da main.

   3.1. Vantagens:

      3.1.1. Poder modificar sem alterar o local principal (main)

      3.1.2. Falcilmente "desligável" (criar/apagar)

      3.1.3. Múlitplas pessoas trabalhando

      3.1.4. Evita conflitos

   3.2. Como criar uma branch:

      git checkout -b Nome

      git branch: mostra as branchs existentes e com asterisco a que você está

      git checkout NomeDaBranch: muda de branch

      git branch -D NomeDaBranch: apaga a branch que você quer

   3.3. Merge (União de branchs - forma um ciclo)

      3.3.1. Pró
         3.3.1.1. Operação não destrutiva
      3.3.2. Contra
         3.3.2.1. Comite extra
         3.3.2.2. Histórico poluído
      
   3.4. Rebase (União de branchs - linear)

      3.4.1. Prós
         3.4.1.1. Evita commits extras
         3.4.1.2. Histórico linear
      3.4.2. Contra
         3.4.2.1. Perde ordem cronológica
      (indicou usar quando for fazer pull)
      
OBS: como fazer Merge e Rebase na seção 5 - Aula 24

4. Extras

   4.1. .gitignore

   4.2. git stash ...

   4.3. alias

   4.4. Tags

   4.5. Revert

   4.6. Apagar tags e brnaches remotos

CURSO FINALIZADO!