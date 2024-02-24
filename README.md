# Gitflow para Repositório de 2 Aplicações

Este repositório contém 2 aplicações, cada uma com uma responsabilidade específica:

1. **Mobile Plataform:** Aplicação multiplataforma construída com o framework `flutter` com a linguagem `dart`, utilizada por usuários para consumo de música, operações de CRUD e compartilhamento de playlists.
2. **Web Plataform:** Aplicação Web construída com o framework `React` com a linguagem `typescript`, utilizada por usuários para consumo de música, operações de CRUD e compartilhamento de playlists.

## Estratégia Gitflow

Este repositório segue a estratégia Gitflow para gerenciamento de branches. Neste modelo, temos dois tipos principais de branches:

1. **Branch `master`:** Esta é a branch principal do repositório. Ela contém o código de produção, que é implantado em ambiente de produção.
2. **Branch `develop`:** Esta é a branch de desenvolvimento. Ela contém o código em desenvolvimento, que está pronto para ser implantado em ambiente de teste.

Além disso, temos outros tipos de branches:

- **Branches `feature/*`:** Estas branches são criadas a partir de `develop` e são usadas para desenvolver novas funcionalidades. Quando uma feature é concluída, ela é mesclada de volta em `develop`.
- **Branches `hotfix/*`:** Estas branches são criadas a partir de `master` e são usadas para corrigir bugs críticos em produção. Quando um hotfix é concluído, ele é mesclado de volta em `master` e `develop`.
- **Branches `release/*`:** Estas branches são criadas a partir de `develop` e são usadas para preparar uma nova versão para produção. Elas incluem testes finais e atualizações de documentação. Quando uma release é concluída, ela é mesclada de volta em `master` e `develop`.

## Executando as Aplicações

Cada aplicação possui sua própria estrutura de diretórios e arquivos específicos. As instruções para executar cada aplicação podem ser encontradas em seus respectivos diretórios. Certifique-se de seguir as instruções corretamente para garantir que as aplicações sejam executadas corretamente.

## Contribuindo

Se você deseja contribuir para este repositório, siga as instruções abaixo:

1. Faça um fork deste repositório.
2. Clone o fork para o seu computador.
3. Crie uma nova branch para a sua contribuição: `git checkout -b feature/nome-da-sua-feature`.
4. Faça as alterações necessárias.
5. Adicione e faça o commit das alterações: `git add . && git commit -m "Mensagem do commit"`.
6. Faça o push das alterações para o seu fork: `git push origin feature/nome-da-sua-feature`.
7. Crie um novo Pull Request.

## Mais Informações

Para mais informações sobre Gitflow, consulte [este guia](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow).

Se você tiver alguma dúvida ou problema, por favor, abra uma [issue](https://github.com/thirochas/spotmusic-frontend/issues) neste repositório.
