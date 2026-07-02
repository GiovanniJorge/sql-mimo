# SQL - Mimo

Códigos relacionados ao curso de SQL da Mimo — coleção de projetos práticos focados em manipulação de dados, consultas SQL e gerenciamento de bancos de dados. Ideal para estudantes que querem aprender SQL aplicado a problemas reais.

## Conteúdo principal
- Projetos práticos que demonstram conceitos fundamentais de SQL (CRUD, JOINs, agregações, etc.).
- Integração com bancos de dados SQLite e Node.js para criar aplicações completas.
- Exemplos de como estruturar e consultar dados de forma eficiente.

## Badges
![Licença](https://img.shields.io/github/license/GiovanniJorge/sql-mimo?style=flat-square)

## Sumário
- [Visão geral](#visão-geral)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Destaques do repositório](#destaques-do-repositório)
- [Como executar](#como-executar)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Autor / Contato](#autor--contato)

## Visão geral
Este repositório organiza pequenos projetos em JavaScript que demonstram conceitos de SQL e gerenciamento de bancos de dados. Cada projeto é independente e pode ser utilizado como referência ou ponto de partida para outros projetos. Os exemplos incluem operações comuns como inserção, leitura, atualização e exclusão de dados (CRUD).

## Estrutura do repositório
Top-level:
```text
├── .gitattributes
├── LICENSE                  # Licença MIT do projeto
├── README.md                # Este arquivo
└── projetos-gerais/         # Projetos práticos de SQL com Node.js
    ├── book-keeper/         # Projeto de gerenciamento de livros e autores
    │   ├── app.js           # Aplicação principal
    │   └── database.js      # Configuração e operações do banco de dados
    ├── task-manager/        # Projeto de gerenciamento de tarefas
    │   ├── app.js           # Aplicação principal
    │   └── database.js      # Configuração e operações do banco de dados
    └── ...                  # Outros projetos e exercícios de fixação desenvolvidos
```

### Como se encaixa:
- O repositório abriga uma variedade de projetos independentes criados ao longo do curso.
- As pastas listadas acima funcionam como exemplos principais de aplicações contidas no diretório `projetos-gerais/`.
- Os projetos usam **SQLite** como banco de dados (arquivo `.db` gerado automaticamente em tempo de execução).

## Destaques do repositório

### Book Keeper
* **Descrição:** Gerenciador de livros e autores que executa operações completas de CRUD e relacionamentos estruturados em tabelas relacionais.
* **Tecnologias:** Node.js, SQLite.

### Task Manager
* **Descrição:** Gerenciador de tarefas focado no controle de estados e registros individuais, manipulando inserções e atualizações via queries parametrizadas.
* **Tecnologias:** Node.js, SQLite.

## Como executar

### Pré-requisitos
- **Node.js** (v14 ou superior)
- **npm** ou **yarn** como gerenciador de pacotes

### Passos para execução

1. **Clone o repositório:**
```bash
git clone [https://github.com/GiovanniJorge/sql-mimo.git](https://github.com/GiovanniJorge/sql-mimo.git)
cd sql-mimo
```

2. **Instale as dependências e execute (Exemplo com Book Keeper):**
```bash
cd projetos-gerais/book-keeper
npm install
node app.js
```

3. **Para executar o Task Manager:**
```bash
cd ../task-manager
npm install
node app.js
```

## Contribuindo
Contribuições são bem-vistas! Se deseja adicionar um novo projeto ou otimizar queries existentes, siga os passos abaixo:

1. Faça um **Fork** do repositório.
2. Crie uma branch com nome descritivo: `feature/novo-projeto` ou `fix/melhorando-queries`.
3. Fazer commits atômicos com mensagens claras.
4. Abrir Pull Request descrevendo as mudanças e o objetivo pedagógico.

## Licença
Este repositório utiliza a licença MIT — consulte o arquivo [LICENSE](LICENSE) na raiz.

## Autor / Contato
- **Autor:** Giovanni Jorge  
- **Repositório:** [https://github.com/GiovanniJorge/sql-mimo](https://github.com/GiovanniJorge/sql-mimo)
