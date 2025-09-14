📊 Controle de Gastos
Aplicação web simples para controle de gastos pessoais, permitindo o cadastro, visualização, edição e exclusão de receitas e despesas.

O projeto foi desenvolvido como parte de uma atividade acadêmica, utilizando uma stack moderna com Spring Boot no backend e Thymeleaf com HTMX no frontend para uma experiência de usuário reativa sem a necessidade de frameworks JavaScript complexos.

✨ Features
- Create: Adicionar novos lançamentos (receitas ou despesas).

- Read: Visualizar todos os lançamentos em uma lista ordenada por data.

- Update: Editar as informações de um lançamento existente.

- Delete: Remover um lançamento da lista.

- Interface Reativa: As operações de CRUD atualizam a lista de lançamentos instantaneamente, sem recarregar a página, graças ao HTMX.

🚀 Tecnologias Utilizadas
Backend:

- Java 17

- Spring Boot 3

- Spring Web

- Spring Data JPA

- Hibernate

- Maven

- Frontend:

- Thymeleaf

- HTMX

- Bootstrap 5

Banco de Dados:

- PostgreSQL (para produção)

- H2 Database (para testes e desenvolvimento local, se preferir)


⚙️ Como Configurar e Executar Localmente

Clone o repositório:

```

git clone https://github.com/seu-usuario/controle-de-gastos.git
cd controle-de-gastos

```

Configure o Banco de Dados (PostgreSQL):

Crie um novo banco de dados no seu PostgreSQL. Ex: controle_gastos_db.

Certifique-se de ter um usuário e senha com permissões para acessar este banco.

Configure as Variáveis de Ambiente:

O projeto utiliza as variáveis de ambiente para a conexão com o banco de dados, conforme definido no arquivo application.properties.

Você precisa definir as seguintes variáveis:

DB_URL: A URL de conexão JDBC. Ex: jdbc:postgresql://localhost:5432/controle_gastos_db

DB_USERNAME: O nome de usuário do seu banco.

DB_PASSWORD: A senha do seu banco.

Dica: Na sua IDE (IntelliJ, VSCode, etc.), você pode configurar essas variáveis na seção "Run/Debug Configurations" para a sua aplicação Spring Boot.

Execute a Aplicação:

Use o Maven para compilar e iniciar o projeto.

```

mvn spring-boot:run

```

Acesse a Aplicação:
Abra seu navegador e acesse http://localhost:8080.

## A aplicação está no ar em:

https://crud-controle-gastos-gvdev.onrender.com/
