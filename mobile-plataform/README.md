# Mobile Plataform

O Mobile Plataform é uma aplicação mobile desenvolvida em Flutter que é responsável pelo fluxo de consumo de músicas.

## Organização dos arquivos
```
├── android/ (Diretório para arquivos relacionados ao Android)
├── ios/ (Diretório para arquivos relacionados ao iOS)
├── lib/ (Diretório para o código-fonte do aplicativo)
│   ├── models/ (Diretório para os modelos de dados do aplicativo)
│   ├── screens/ (Diretório para as telas do aplicativo)
│   ├── services/ (Diretório para os serviços do aplicativo, como serviços de rede ou armazenamento local)
│   ├── widgets/ (Diretório para os widgets reutilizáveis do aplicativo)
│   ├── main.dart (Arquivo principal do aplicativo)
├── test/ (Diretório para testes automatizados)
├── pubspec.yaml (Arquivo de configuração do Flutter, onde você especifica as dependências do aplicativo)
├── README.md (Arquivo de documentação do projeto)
```
## Executando a Aplicação

Para executar a aplicação em um ambiente local, siga as instruções abaixo:

1. Clone o repositório para o seu computador: `git clone https://github.com/seu-usuario/mobile-plataform.git`.
2. Navegue até o diretório da aplicação: `cd mobile-plataform`.
3. Execute o comando para instalar as dependências: `flutter pub get`.
4. Execute o comando para iniciar a aplicação: `flutter run`.

Agora a aplicação está sendo executada localmente em http://localhost:8084.

## Deploy em Ambiente de Produção

Para implantar a aplicação em um ambiente de produção, siga as instruções abaixo:

1. Crie uma nova instância de servidor na nuvem.
2. Clone o repositório para o servidor: `git clone https://github.com/seu-usuario/mobile-plataform.git`.
3. Navegue até o diretório da aplicação: `cd mobile-plataform`.
4. Execute o comando para instalar as dependências: `flutter pub get`.
5. Execute o comando para criar o pacote de distribuição: `flutter build apk`.
6. Execute o comando para iniciar a aplicação: `flutter run`.

Agora a aplicação está sendo executada em http://seu-endereco-de-producao:8084.

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

Se você tiver alguma dúvida ou problema, por favor, abra uma [issue](https://github.com/thirochas/spotmusic-frontend/issues) neste repositório.