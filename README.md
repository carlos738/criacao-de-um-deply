# criacao-de-um-deploy
# 🚀 Deploy de Aplicação PHP com MySQL usando Docker (para GitHub Codespaces)

Este projeto demonstra como criar uma aplicação simples em PHP que se conecta a um banco de dados MySQL, utilizando Docker e Docker Compose. Foi estruturado para funcionar perfeitamente dentro do GitHub Codespaces.

---

## 📁 Estrutura de Arquivos

---

## ⚙️ Tecnologias Usadas

- PHP 8.2 com Apache
- MySQL 5.7
- Docker e Docker Compose
- GitHub Codespaces

---

## 📦 Etapas do Projeto

### 1. `index.php`

Arquivo PHP que realiza a conexão com o banco de dados MySQL via `mysqli` e exibe mensagem de sucesso ou erro.

### 2. `Dockerfile`

Define a imagem da aplicação PHP com Apache. Instala a extensão `mysqli` e copia o código para o diretório do servidor.

### 3. `docker-compose.yml`

Orquestra dois serviços:

- **php-app**: container com a aplicação PHP
- **db**: container com a base MySQL

Utiliza volumes para persistência de dados e variáveis de ambiente para conexão.

### 4. `.devcontainer/devcontainer.json`

Permite que o Docker funcione dentro do GitHub Codespaces. Faz o build dos containers automaticamente e expõe a porta correta para acesso.

---

## 🚀 Como Usar no GitHub Codespaces

1. Crie um repositório com os arquivos acima.
2. Abra um Codespace a partir do repositório.
3. O ambiente será criado automaticamente.
4. Vá até a aba **Ports** e clique na porta **8080** para abrir a aplicação.

---

## ✅ Resultado Esperado

Ao acessar a aplicação, você verá uma mensagem:


---

## 💡 Extras

Você pode estender este projeto com:

- Interface HTML para exibir os dados do banco
- Cadastro de usuários com formulários
- Integração com Laravel, PDO ou APIs REST

---

### 📬 Dúvidas ou sugestões?

Fique à vontade para abrir issues ou contribuições! 😄


