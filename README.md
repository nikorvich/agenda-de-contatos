# 📇 Agenda de Contatos (MVC)

Aplicação de agenda de contatos desenvolvida em JavaScript (ES6+), utilizando a arquitetura MVC (Model-View-Controller), com separação de responsabilidades e persistência local de dados.

## Funcionalidades

- **Cadastro:** Adição de novos contatos por meio de formulário.
- **Listagem:** Exibição dinâmica dos contatos cadastrados ao carregar a aplicação.
- **Exclusão:** Remoção de contatos por meio de identificador único.
- **Persistência:** Armazenamento automático dos dados utilizando `localStorage`.

## Especificações Técnicas

- **Linguagem:** JavaScript (ES6+).
- **Módulos:** Utilização de ES6 Modules (`import`/`export`).
- **Arquitetura:** MVC (Model-View-Controller).
- **Persistência:** `localStorage`.
- **Ponto de Entrada:** Inicialização da aplicação por meio do arquivo `main.mjs`.

## Estrutura da Aplicação

- **Model:** Responsável pela representação e manipulação dos dados.
- **View:** Responsável pela interface e renderização das informações.
- **Controller:** Responsável pela comunicação entre Model e View e pelo controle das ações do usuário.
