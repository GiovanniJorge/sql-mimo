# SQL - Mimo
Códigos relacionados ao curso de SQL da Mimo — coleção de projetos práticos focados em manipulação de dados, consultas SQL e gerenciamento de bancos de dados. Ideal para estudantes que querem aprender SQL aplicado a problemas reais.

## Conteúdo principal
- Projetos práticos que demonstram conceitos fundamentais de SQL (CRUD, JOINs, agregações, etc.).
- Integração com bancos de dados SQLite e Node.js para criar aplicações completas.
- Exemplos de como estruturar e consultar dados de forma eficiente.

## Badges
- Licença: MIT (ver arquivo LICENSE)

## Sumário
- [Visão geral](#visão-geral)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Como executar](#como-executar)
- [Boas práticas](#boas-práticas)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Autor / Contato](#autor--contato)

## Visão geral
Este repositório organiza pequenos projetos em JavaScript que demonstram conceitos de SQL e gerenciamento de bancos de dados. Cada projeto é independente e pode ser utilizado como referência ou ponto de partida para outros projetos. Os exemplos incluem operações comuns como inserção, leitura, atualização e exclusão de dados (CRUD).

## Estrutura do repositório
Top-level:
- `.gitattributes`
- `LICENSE`                  — licença MIT do projeto
- `README.md`                — este arquivo
- `projetos-gerais/`         — projetos práticos de SQL com Node.js
  - `book-keeper/`           — projeto de gerenciamento de livros e autores
    - `app.js`               — aplicação principal
    - `database.js`          — configuração e operações do banco de dados
  - `task-manager/`          — projeto de gerenciamento de tarefas
    - `app.js`               — aplicação principal
    - `database.js`          — configuração e operações do banco de dados

### Como se encaixa
- Cada pasta em `projetos-gerais/` é um projeto independente com sua própria aplicação e banco de dados.
- A estrutura segue um padrão comum: `app.js` para a lógica principal e `database.js` para operações SQL.
- Os projetos usam **SQLite** como banco de dados (arquivo `.db` gerado em tempo de execução).

## Como executar

### Pré-requisitos
- Node.js 14+ instalado
- npm ou yarn para gerenciar dependências

### Passos gerais

1. **Clone o repositório:**
```bash
git clone https://github.com/GiovanniJorge/sql-mimo.git
cd sql-mimo
```

2. **Instale as dependências** (se necessário):
```bash
cd projetos-gerais/book-keeper
npm install
```

3. **Execute um projeto:**
```bash
# Para o projeto book-keeper
cd projetos-gerais/book-keeper
node app.js

# Para o projeto task-manager
cd projetos-gerais/task-manager
node app.js
```

### Exemplos por projeto

**Book Keeper** — Gerenciador de livros e autores:
```bash
cd projetos-gerais/book-keeper
node app.js
# Executará operações de CRUD em uma tabela de livros
```

**Task Manager** — Gerenciador de tarefas:
```bash
cd projetos-gerais/task-manager
node app.js
# Executará operações de CRUD em uma tabela de tarefas
```

## Boas práticas

- **Documentação:** Cada arquivo `.js` deve incluir um comentário no topo explicando o objetivo do projeto e as operações SQL disponíveis.
- **Separação de responsabilidades:** Mantenha a lógica SQL em `database.js` e a lógica de aplicação em `app.js`.
- **Tratamento de erros:** Use try/catch para capturar erros de banco de dados e exibir mensagens claras.
- **Queries parametrizadas:** Sempre use prepared statements para evitar SQL injection.
- **Nomes consistentes:** Use nomes descritivos para variáveis, tabelas e colunas (em inglês para padronização).

## Contribuindo
Contribuições são bem-vindas (ex.: novos projetos, melhorias nas queries, comentários adicionais, correções). Fluxo sugerido:

1. Fork do repositório.
2. Criar branch com nome descritivo: `feature/novo-projeto` ou `fix/melhorando-queries`.
3. Fazer commits atômicos com mensagens claras.
4. Abrir Pull Request descrevendo as mudanças e o objetivo pedagógico.
5. Se possível, inclua exemplos de uso e documentação.

## Testes e automação (opcional)
- Poderia ser adicionado um Makefile ou script bash para facilitar execução em lote.
- Para verificação automática, adicionar um workflow (GitHub Actions) que valide a execução de cada projeto.

## Licença
Este repositório utiliza a licença MIT — consulte o arquivo `LICENSE` na raiz.

## Autor / Contato
Autor: Giovanni Jorge  
Repositório: https://github.com/GiovanniJorge/sql-mimo
