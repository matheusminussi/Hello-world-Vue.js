# Projeto hello-world com Vue.js
**Apresentação do Projeto Full Stack - Vue.js + Java Spring Boot**

**1. Instalação e Configuração do Ambiente de Desenvolvimento**

Tecnologias utilizadas:
- Frontend: Vue.js
- Backend: Java com Spring Boot
- IDE: IntelliJ IDEA
- Banco de dados: PostgreSQL
- Gerenciador de dependências: Maven

Passos iniciais:
1. Instalar o Node.js e npm (para rodar o Vue.js)
2. Instalar o Vue CLI com: npm install -g @vue/cli
3. Criar o projeto Vue com: vue create hello-world
4. Instalar o IntelliJ IDEA e importar o backend (Java)

**2. Configuração do Banco de Dados: PostgreSQL**
- Instale o PostgreSQL a partir do site oficial.
- Crie um banco de dados chamado 'meubanco' com usuário e senha.
- No backend Spring Boot, configure o acesso no application.properties:

```
spring.datasource.url=jdbc:postgresql://localhost:5432/meubanco
spring.datasource.username=usuario
spring.datasource.password=senha
```
**3. Backend: Java + Spring Boot com Maven**
- O backend utiliza Maven como gerenciador de dependências.
- No IntelliJ, importe o projeto como Maven Project.
- O arquivo pom.xml contém as dependências essenciais (Spring Web, PostgreSQL, etc.).
- A estrutura segue o padrão MVC (Model, View, Controller).
Apresentação do Projeto Full Stack - Vue.js + Java Spring Boot

**4. Frontend: Vue.js**
- Criado com Vue CLI: vue create hello-world
- O projeto possui componentes Vue com integração via API REST.
- A comunicação é feita com axios:

```
axios.get('http://localhost:8080/api/hello').then(...)
```
- Para rodar o frontend:

```
 cd hello-world
 npm run serve
```
**5. Executando a Aplicação Completa**
1. Inicie o backend com IntelliJ (Spring Boot app).
2. Inicie o frontend com: npm run serve
3. Acesse o frontend via navegador (geralmente em http://localhost:8081)
4. A aplicação fará requisições para o backend (http://localhost:8080)
