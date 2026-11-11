# DevOps Hub - Vitrine de Inovação e Talentos

# Sobre o Projeto
O **DevOps Hub** é uma aplicação web desenvolvida para a Unidade Curricular de Projeto e Engenharia de Software (Curso de Análise e Desenvolvimento de Sistemas). A plataforma atua como uma vitrine centralizada onde squads de estudantes cadastram seus projetos integradores de TI, facilitando a visualização por mentores, avaliadores e empresas parceiras.

---

# Funcionalidades Principais
- **Cadastro de Projetos:** Registro de novos trabalhos com título, descrição, tecnologias e link do repositório.
- **Vitrine de Soluções:** Listagem pública dos projetos cadastrados em formato de cards.
- **Filtros de Pesquisa:** Busca rápida por nome do projeto ou tecnologia utilizada.

---

# Tecnologias Utilizadas
- **Front-end:** HTML5, CSS3, JavaScript (ES6+)
- **Back-end:** Java (Spring Boot)
- **Banco de Dados:** SQLite
- **Versionamento:** Git & GitHub

---

# Pré-requisitos para Execução
Antes de começar, você precisará ter instalado em sua máquina:
- [JDK 17 ou superior](https://www.oracle.com/java/technologies/downloads/)
- [Maven](https://maven.apache.org/) (opcional, se usar o wrapper `./mvnw`)
- Um navegador web atualizado (Google Chrome, Firefox, Edge)

---

# Como Baixar e Executar o Projeto

### 1. Clonar o Repositório
```bash
git clone https://github.com/SEU-USUARIO/devops-hub.git
cd devops-hub
```

### 2. Executar o Back-end (Spring Boot + SQLite)
Navegue até a pasta do back-end e execute o projeto:
```bash
cd backend
./mvnw spring-boot:run
```
> O servidor iniciará na porta `8080` (http://localhost:8080) e o banco de dados `database.db` será criado automaticamente na primeira execução.

### 3. Executar o Front-end
1. Navegue até a pasta `frontend`.
2. Abra o arquivo `index.html` em qualquer navegador web (ou utilize a extensão *Live Server* no VS Code).

---

# Como Testar a Aplicação
1. Abra a página `index.html`.
2. Preencha o formulário de cadastro com dados de um projeto de teste (ex: Título: *Sistema de Estoque*, Tecnologias: *Java, React*).
3. Clique em **Cadastrar Projeto**.
4. Verifique se o card do novo projeto apareceu automaticamente na seção **Projetos Cadastrados**.

---

# Integrantes do Squad (DevOps Squad)
- Componente 1 - RA: XXXXXXX
- Componente 2 - RA: XXXXXXX
- Componente 3 - RA: XXXXXXX