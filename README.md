# 📚 Base de Conhecimento – Imersão Dev Alura + Google Gemini

Este projeto foi desenvolvido durante a **Imersão Dev da Alura em parceria com o Google Gemini**, com o objetivo de criar uma aplicação web simples para consulta de uma base de conhecimento sobre **linguagens, frameworks, bancos de dados e ferramentas do ecossistema de desenvolvimento**.

A aplicação utiliza **HTML, CSS e JavaScript puro**, consumindo dados de um arquivo JSON local e renderizando dinamicamente os resultados conforme a busca do usuário.

---

## 🚀 Funcionalidades

- 🔎 Campo de busca por nome ou descrição
- 📄 Renderização dinâmica de cards com:
  - Nome da tecnologia
  - Ano de criação
  - Descrição
  - Link oficial
- 📂 Consumo de dados via arquivo `data.json`
- 🎨 Interface responsiva e moderna
- 📱 Adaptação para dispositivos móveis
- ⚡ Carregamento dos dados apenas na primeira busca (cache em memória)

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** – Estrutura da aplicação
- **CSS3** – Estilização e responsividade
- **JavaScript (ES6+)** – Lógica da aplicação
- **Fetch API** – Consumo de dados JSON
- **Google Fonts** – Fonte *Quicksand*
- **VS Code + Extensão Google Gemini** – Apoio no desenvolvimento

---

## 📁 Estrutura do Projeto

```bash
├── index.html      # Estrutura principal da aplicação
├── style.css       # Estilos globais e responsividade
├── script.js       # Lógica de busca e renderização
├── data.json       # Base de dados das tecnologias
└── README.md       # Documentação do projeto
