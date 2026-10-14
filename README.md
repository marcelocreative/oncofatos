# 📖 tesenews

> Reduto para discussões profundas, exegese bíblica e história da igreja.

O **tesenews** é uma plataforma colaborativa de publicação, estudo e debate teológico, projetada para promover conteúdos de alto valor exegético em um ambiente sem distrações, focado em texto e na construção de reputação comunitária.

---

## 🛠️ Engenharia e Arquitetura de Software

Este projeto é desenvolvido com foco em fundamentos de engenharia defensiva, alta disponibilidade e práticas de desenvolvimento moderno:

- **Arquitetura de Produção:** Aplicação web completa com renderização no servidor (SSR) e APIs RESTful.
- **Banco de Dados Relacional:** Modelagem, migrações e persistência com PostgreSQL.
- **Infracódigo & Conteinerização:** Ambiente totalmente isolado e reprodutível via Docker e Docker Compose.
- **Qualidade & Automação:** Suíte de testes automatizados e pipeline de Integração Contínua (CI/CD) via GitHub Actions.

---

## 🚦 Como executar o ambiente localmente

```bash
# 1. Clone o repositório
$ git clone [https://github.com/SEU-USUARIO/tesenews.git](https://github.com/SEU-USUARIO/tesenews.git)

# 2. Acesse o diretório do projeto
$ cd tesenews

# 3. Suba o ambiente e dependências (Docker)
$ npm run dev
