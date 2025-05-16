
# Cadastro de Séries em .NET 7

Este projeto é uma aplicação de console desenvolvida em C# com .NET 7, com o objetivo de simular um sistema básico de cadastro e gerenciamento de séries. Trata-se de um exercício prático ideal para quem está aprendendo programação orientada a objetos e deseja entender como estruturar uma aplicação simples em C#.

## Proposito 

Fornecer uma base sólida para aplicar os conceitos fundamentais de desenvolvimento com C# e .NET, incluindo:

- Programação orientada a objetos
- Estruturação de menus no console
- Manipulação de listas
- Organização de código em classes e métodos

Exercitar fundamentos de C#: O projeto foi desenvolvido com o objetivo didático de praticar conceitos básicos da linguagem C#, como classes, objetos, herança, enums e listas genéricas.

Explorar a programação orientada a objetos (POO): Ele serve como um primeiro contato com a modelagem de entidades e aplicação de princípios como encapsulamento e separação de responsabilidades.

Simular operações CRUD de forma simples: Permite que o desenvolvedor entenda, de forma prática, como criar menus interativos e implementar funcionalidades como criar, listar, atualizar e excluir registros (nesse caso, séries).

Aprender estruturação e organização de código: Ensina a separar lógica de dados, lógica de negócios e interface com o usuário, mesmo dentro de uma aplicação de console.

### Utilidade Prática
Base para projetos maiores: Apesar de simples, a estrutura pode ser evoluída para APIs, aplicações web ou bancos de dados persistentes.
O projeto cobre vários pontos frequentemente exigidos em testes de lógica e C#, como uso de enum, List<T>, switch-case, e organização modular.



## Funcionalidades

- Listar séries cadastradas
- Adicionar uma nova série
- Atualizar dados de uma série existente
- Excluir (marcar como inativa) uma série
- Visualizar detalhes de uma série
- Validação básica de entrada

## Tecnologias Utilizadas

- C#
- .NET 7 SDK
- Aplicação de console (Console Application)

## Estrutura do Projeto

```
Cadastro-de-Series/
├── Program.cs             # Ponto de entrada da aplicação
├── Serie.cs               # Classe de modelo da entidade Série
├── SerieRepositorio.cs    # Classe responsável pelo armazenamento e operações CRUD
├── EntidadeBase.cs        # Classe base para entidades com ID
├── Genero.cs              # Enumeração com os gêneros disponíveis
└── Interfaces.cs          # Interface do repositório
```

## Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/luxasfn/Cadastro-de-S-ries-em-.NET7.git
```

2. Certifique-se de ter o .NET 7 SDK instalado.

3. Execute o projeto pelo terminal ou pela sua IDE:

```bash
dotnet run
```

## Aprendizados

Este projeto proporcionou a prática e compreensão dos seguintes tópicos:

### Organização de código orientado a objetos

- Uso de classes para representar entidades do sistema (como `Serie`)
- Aplicação de herança simples com uma classe base (`EntidadeBase`)
- Uso de enum (`Genero`) para facilitar opções pré-definidas

### Lógica de CRUD no console

- Criação de menus interativos com `Console.ReadLine()` e `switch-case`
- Tratamento básico de erros de entrada do usuário
- Simulação de exclusão lógica com marcação de objetos como "excluídos"

### Estrutura de repositório

- Implementação de um repositório interno para abstrair operações com a lista de séries
- Separação clara entre lógica de interface, lógica de domínio e persistência em memória

### Prática com o .NET CLI

- Criação e execução de projetos no terminal com `dotnet new console` e `dotnet run`
- Familiaridade com o ciclo de desenvolvimento em ambiente de console

## Licença

Este projeto está sob a licença MIT. Livre para uso e modificação.
