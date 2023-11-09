# DIO Resumos Git e GitHub

Repositório para armazenar resumos do curso [Versionamento de código DIO](https://www.dio.me/).

## Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://doc.github.com/)

## Resumos das Aulas

| Aulas                                     | Resumos       |
|-------------------------------------------|---------------|
| Gravando alterações no repositório Local 1 | [Resumos]()   |
| Gravando alterações no repositório Local 2 | [Resumos]()   |

| Iniciar o Git na pasta                    | [Resumos]()   |
|-------------------------------------------|---------------|
| ```git init```                            | Inicializa um repositório Git na pasta.  |
| ```git status```                          | Verifica o estado do seu repositório.    |
| ```git add <file>```                      | Adiciona um arquivo ao stage.            |
| ```git commit -m"<file>"```               | Realiza um commit com uma mensagem.     |

| Desfazer um commit ou mudança             | [Resumos]()   |
|-------------------------------------------|---------------|
| ```git restore <file>```                  | Desfaz alterações em um arquivo.        |
| ```git restore --staged <file>```         | Remove um arquivo do stage.             |
| ```git reset --soft```                    | Desfaz o último commit mantendo as alterações.  |
| ```git reset --mixed <hash>```            | Desfaz o commit e mantém as alterações no stage.  |
| ```git reset --hard <hash>```             | Desfaz o commit e as alterações no stage.|

| Verificar log de arquivos alterados        | [Resumos]()   |
|-------------------------------------------|---------------|
| ```git log```                             | Exibe o histórico de commits.           |
| ```git reflog```                          | Mostra o histórico de referências, útil para recuperar commits perdidos. |

| Se conectar ao servidor online GitHub      | [Resumos]()   |
|-------------------------------------------|---------------|
| ```git remote set-url```                   | Define a URL do repositório remoto.    |
| ```git remote add origin```                | Adiciona um repositório remoto chamado "origin".  |

| Aplicar alterações e puxar para o meu arquivo | [Resumos]()  |
|----------------------------------------------|--------------|
| ```git push -u - origin main```               | Envia as alterações para o repositório remoto. |
| ```git pull```                               | Atualiza o repositório local com as alterações do repositório remoto. |

## Branches
Cria ramificações do seu projeto, para testes, como se fosse um universo paralelo onde você pode implementar mudanças sem impactar no projeto principal.

```bash
git checkout -b <branch>  # Cria e muda para uma nova branch.
git checkout main         # Muda de volta para a branch principal.
git branch -v             # Lista todas as branches.

git merge                 # Mescla alterações de uma branch para outra.
git branch -d <branch>    # Deleta uma branch.


