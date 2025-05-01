# Blog com Container Apps

Este projeto é um exemplo de como criar um **Blog** simples utilizando **Container Apps** (Docker/Kubernetes) para facilitar a implantação e a escalabilidade do aplicativo. O blog será composto por um back-end e um front-end, que serão containerizados para execução em qualquer ambiente de produção.

## Funcionalidades

- **Postagens**: Criação, leitura, atualização e exclusão de postagens.
- **Comentários**: Permite que os usuários deixem comentários nas postagens.
- **Interface de Usuário**: Um front-end simples para visualizar e interagir com as postagens.
- **API REST**: Uma API RESTful para manipular os dados de postagens e comentários.

## Tecnologias Utilizadas

- **Back-End**:
  - **Python** (Flask/Django/FastAPI): Framework para construir a API do blog.
  - **Banco de Dados**: PostgreSQL (ou qualquer outro banco de dados).
  - **Docker**: Para containerizar o back-end e o banco de dados.

- **Front-End**:
  - **React** (ou outro framework JS): Para criar a interface de usuário.
  - **Docker**: Para containerizar o front-end.

- **DevOps**:
  - **Docker Compose**: Para orquestrar a execução de múltiplos containers.
  - **Kubernetes** (opcional): Para implantar os containers em um ambiente de produção escalável.

## Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/blog-container-apps.git
cd blog-container-apps
