# 🎵 Screen Sound

Aplicação de console desenvolvida em **C#** para cadastro, avaliação e gerenciamento de bandas e álbuns.

O projeto foi desenvolvido com foco na prática de **Programação Orientada a Objetos** utilizando o ecossistema .NET.

## Funcionalidades

-  Cadastro de bandas
-  Cadastro de álbuns
-  Cadastro de músicas
-  Avaliação de bandas
-  Avaliação de álbuns
-  Cálculo da média das avaliações
-  Listagem de bandas cadastradas
-  Exibição dos detalhes de uma banda
-  Menu interativo pelo terminal

## Tecnologias

- C#
- .NET
- LINQ
- Programação Orientada a Objetos

## Conceitos praticados

- Classes e objetos
- Construtores
- Propriedades
- Encapsulamento
- Interfaces
- Polimorfismo
- Coleções (`List` e `Dictionary`)
- LINQ
- Expressões lambda
- Separação de responsabilidades

## Estrutura do projeto

    ScreenSound/
    ├── Menus/
    │   ├── Menu.cs
    │   ├── MenuAvaliarAlbum.cs
    │   ├── MenuAvaliarBanda.cs
    │   ├── MenuExibirDetalhes.cs
    │   ├── MenuMostrarBandas.cs
    │   ├── MenuRegistrarAlbum.cs
    │   ├── MenuRegistrarBanda.cs
    │   └── MenuSair.cs
    │
    ├── Modelos/
    │   ├── Album.cs
    │   ├── Avaliacao.cs
    │   ├── Banda.cs
    │   ├── IAvaliavel.cs
    │   └── Musica.cs
    │
    ├── Program.cs
    └── ScreenSound.csproj

## Como executar

### Pré-requisitos

É necessário ter o **.NET SDK** instalado.

Verifique a instalação:

    dotnet --version

### Clone o repositório

    git clone https://github.com/elitohn/screen-sound-csharp.git

Acesse o diretório:

    cd screen-sound-csharp

Entre na pasta da aplicação:

    cd ScreenSound

Execute o projeto:

    dotnet run

## Utilização

Após iniciar a aplicação, será exibido um menu interativo no terminal.

Através dele é possível cadastrar bandas, registrar álbuns, realizar avaliações e consultar os detalhes das bandas cadastradas.

## Objetivo

O **Screen Sound** é um projeto desenvolvido durante meus estudos de **C# e .NET**, com o objetivo de colocar em prática conceitos de Programação Orientada a Objetos e desenvolver uma aplicação funcional utilizando C#.

## Autor

Desenvolvido por **Wellyton Huan**.

[GitHub](https://github.com/elitohn)

---
