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
    
    2.9. add README.md
    
    2.10. git commit -am "comentário"

    2.11. git push origin main
