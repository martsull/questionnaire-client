# 📝 Questionnaire — Form & Survey Builder

**Questionnaire** is a powerful web application for creating and completing surveys and forms. Built with React and Node.js, it uses PostgreSQL for data storage and Typesense for lightning-fast full-text search. It supports multilingual interfaces, authentication, statistics visualization, drag-and-drop interactions, and integrations with external systems like Odoo, Salesforce, and Power Automate.

🔗 **Repositories**:
- 🌐 [Client (React)](https://github.com/martsull/questionnaire-client)
- 🔧 [Server (Node.js + Express)](https://github.com/martsull/questionnaire-server)
- 🔍 [Typesense Search Engine](https://github.com/martsull/quiz-typesense)

---

## ✨ Features

- 🌍 **Multilingual support**: English and Spanish, with persistent language preferences
- 🌙 **Themes**: Light and dark modes with session persistence
- 🔐 **Authentication**:
  - JWT-based authentication
  - GitHub OAuth login
- 🧑‍💼 **Admin panel**:
  - Block/unblock users
  - Promote/demote roles
  - Delete users
- 📊 **Home page**:
  - 10 latest created forms
  - Top 5 most popular forms (by number of responses)
  - Trending tags
- 🔎 **Search**:
  - Instant full-text search powered by **Typesense**
  - Search field available on every page

---

## 🛠 Technologies

- ⚛️ React + TypeScript
- 🔧 Node.js + Express
- 🗄 PostgreSQL + Sequelize ORM
- 🎨 Bootstrap
- 🔍 Typesense (full-text search)
- 🔑 JWT + GitHub OAuth
- 📊 Google Charts
- 🧩 Integrations with Odoo, Salesforce, Power Automate

---

## 🧰 Form Builder

Registered users can create surveys and forms with:
- A title, description, theme, and tags
- Public or private visibility

### 🧪 Question Types:
- Single-line text
- Multi-line text
- Positive number
- Single choice (radio)
- Multiple choice (checkbox)

- 📦 Questions can be reordered using **drag-and-drop**
- 📈 **Statistics**:
  - Creators and admins can access detailed analytics for responses
  - Built using **Google Charts**

---

## 🤝 Integrations

- 🔗 **Salesforce**:
  - Create accounts and contacts directly from the platform  
  
- 🧾 **Odoo**:
  - Generate API keys and retrieve statistics for forms directly in Odoo  
  
- 📬 **Power Automate**:
  - Support requests are sent in JSON format, processed, emailed to the admin, and trigger notifications via Power Automate  
