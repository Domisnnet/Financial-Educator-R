![GitHub repo size](https://img.shields.io/github/repo-size/Domisnnet/Financial-Educator-React?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/Domisnnet/Financial-Educator-React?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/Domisnnet/Financial-Educator-React?style=for-the-badge)

<h2 id="sobre-o-projeto">1. Educador Financeiro Inteligente 💰📈</h2>

![Status do Deploy](https://img.shields.io/badge/Status-Online-brightgreen)
![Tecnologias](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
[![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/Financial-Educator-React/blob/main/LICENSE)
![Educador Financeiro](src/assets/images/financial.png)

O **Educador Financeiro Inteligente** é uma plataforma pensada para jovens universitários e pessoas que estão começando a trabalhar. O objetivo é ajudar o usuário a controlar gastos, criar metas simples de economia e receber orientações práticas para evitar que o dinheiro acabe no início do mês.

A proposta prioriza uma experiência clara, amigável e objetiva, com recomendações personalizadas com base em renda mensal, idade e objetivos financeiros. Tudo foi pensado para ser fácil de entender, mesmo para quem está dando os primeiros passos na organização financeira.

---

## 📚 Tabela de Conteúdo

| 💻 O Projeto | 🛠️ Técnico | 🤝 Comunidade |
| :---: | :---: | :---: |
| [![1. Sobre](https://img.shields.io/badge/1%20-%20Sobre-4CAF50)](#sobre-o-projeto) | [![5. Destaques](https://img.shields.io/badge/5%20-%20Destaques-607D8B)](#destaques-tecnicos) | [![9. Código](https://img.shields.io/badge/9%20-%20Código-795548)](#codigo-fonte) |
| [![2. Techs](https://img.shields.io/badge/2%20-%20Techs-2196F3)](#tecnologias-utilizadas) | [![6. Deploy](https://img.shields.io/badge/6%20-%20Deploy-009688)](#fluxo-de-deploy) | [![10. Créditos](https://img.shields.io/badge/10%20-%20Créditos-607D8B)](#créditos) |
| [![3. Acessar](https://img.shields.io/badge/3%20-%20Acessar-FF9800)](#como-acessar) | [![7. Contribuir](https://img.shields.io/badge/7%20-%20Contribuir-3F51B5)](#como-contribuir) | [![11. Licença](https://img.shields.io/badge/11%20-%20Licença-E91E63)](#licenca) |
| [![4. Recursos](https://img.shields.io/badge/4%20-%20Funcionalidades-9C27B0)](#funcionalidades) | [![8. FAQ](https://img.shields.io/badge/8%20-%20FAQ-FFC107)](#faq) | [![12. Perfil](https://img.shields.io/badge/12%20-%20Perfil-212121)](#perfil-do-github) |

---

<h2 id="tecnologias-utilizadas">2. ⚙️ Tecnologias Utilizadas</h2>

| Camada | Tecnologias | Descrição |
| :--- | :--- | :--- |
| **Core** | ![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=white) | Framework SPA moderno baseado em componentes funcionais. |
| **Linguagem** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Código tipado para mais segurança e manutenção. |
| **Build Tool** | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) | Ambiente rápido de desenvolvimento e build otimizado. |
| **Backend/Host** | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) | Authentication, Firestore, Storage e Hosting. |
| **CI/CD** | ![Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) | Automação de builds e deploys contínuos. |

---

<h2 id="como-acessar">3. 🚀 Como Acessar</h2>

Experimente o Educador em tempo real clicando no botão abaixo:

<div align="left">
  <a href="https://studio--studio-6049017955-446d7.us-central1.hosted.app/" target="_blank">
    <img alt="Botão Acessar" src="src/assets/images/botão.webp" height="70" width="70" />
  </a>
</div>

---

<h2 id="funcionalidades">4. 🧩 Funcionalidades Principais</h2>

| Funcionalidade | Descrição |
| :--- | :--- |
| 💰 **Controle simples de gastos** | Cadastro de receitas e despesas com visualização clara do saldo mensal. |
| 📊 **Painel de gastos** | Resumo rápido para entender onde o dinheiro está sendo usado. |
| ⚠️ **Alertas de despesas exageradas** | Avisos quando uma categoria ultrapassa limites recomendados. |
| 🎯 **Simulação de metas de economia** | Criação de metas pequenas e realistas com base na renda disponível. |
| 🤖 **Dicas personalizadas** | Recomendações ajustadas conforme renda mensal, idade e objetivos. |
| 📱 **Responsividade** | Layout adaptativo para Desktop, Tablet e Mobile. |
| ☁️ **Sincronização** | Dados na nuvem via Cloud Firestore. |
| 🔐 **Login Seguro** | Autenticação com Firebase Authentication. |

---

<h2 id="destaques-tecnicos">5. 💻 Destaques Técnicos</h2>

### ✔️ Arquitetura Baseada em Componentes

Cada funcionalidade é separada em componentes independentes, permitindo reutilização, baixo acoplamento e organização clara.

### ✔️ Organização por Responsabilidade

```text
components/  pages/  hooks/  contexts/  services/  firebase/  utils/  assets/
```

Cada diretório possui uma responsabilidade específica, facilitando manutenção e evolução do projeto.

### ✔️ Tipagem com TypeScript

Todo o código utiliza TypeScript, proporcionando:

- Mais segurança durante o desenvolvimento.
- Melhor suporte da IDE.
- Prevenção de erros em tempo de compilação.
- Interfaces mais claras para o time.

### ✔️ Firebase Cloud

Infraestrutura em nuvem com:

- Authentication.
- Cloud Firestore.
- Storage.
- Hosting.

---

<h2 id="fluxo-de-deploy">6. 📦 Fluxo de Deploy</h2>

O deploy utiliza Firebase Hosting integrado ao GitHub.

```bash
npm run build
firebase login
firebase init hosting
firebase deploy
```

Após o deploy, a aplicação ficará disponível na URL configurada pelo Firebase Hosting.

---

<h2 id="como-contribuir">7. 🤝 Como Contribuir</h2>

Siga os passos abaixo para fortalecer este projeto:

| Fase | Ação | Link / Comando |
| :---: | :--- | :--- |
| **01** | **Fork** | [![Fork](https://img.shields.io/badge/-Fazer%20Fork-blue?style=flat-square&logo=github)](https://github.com/Domisnnet/Financial-Educator-React/fork) |
| **02** | **Branch** | `git checkout -b feature/nova-funcionalidade` |
| **03** | **Commit** | `git commit -m 'feat: add nova funcionalidade'` |
| **04** | **Push** | `git push origin feature/nova-funcionalidade` |
| **05** | **PR** | [![Abrir PR](https://img.shields.io/badge/-Abrir%20PR-green?style=flat-square&logo=git)](https://github.com/Domisnnet/Financial-Educator-React/compare) |

### 🐛 Encontrou um problema?

[![Issues Abertas](https://img.shields.io/github/issues/Domisnnet/Financial-Educator-React?style=flat-square&color=red&logo=github)](https://github.com/Domisnnet/Financial-Educator-React/issues)
[![Report Bug](https://img.shields.io/badge/Reportar-Erro-critical?style=flat-square&logo=github)](https://github.com/Domisnnet/Financial-Educator-React/issues/new)

---

<h2 id="faq">8. 🧠 Perguntas Frequentes</h2>

<details>
<summary><strong>O projeto é gratuito? ❓</strong></summary>
<p>✅ <strong>Resposta:</strong> Sim. O projeto é open source sob licença MIT.</p>
</details>

<details>
<summary><strong>Posso utilizar como base para estudos? ❓</strong></summary>
<p>✅ <strong>Resposta:</strong> Sim. O objetivo é servir como referência para desenvolvimento Front-end com React e Firebase. Só não se esqueça de dar os devidos créditos.</p>
</details>

<details>
<summary><strong>Existe versão Mobile? ❓</strong></summary>
<p>✅ <strong>Resposta:</strong> Sim. A aplicação possui layout responsivo para Desktop, Tablet e Mobile.</p>
</details>

<details>
<summary><strong>O projeto utiliza Backend próprio? ❓</strong></summary>
<p>❌ <strong>Resposta:</strong> Não. Toda a infraestrutura baseia-se no Firebase.</p>
</details>

<details>
<summary><strong>O projeto aceita contribuições? ❓</strong></summary>
<p>✅ <strong>Resposta:</strong> Sim. Issues, Pull Requests e sugestões são sempre bem-vindas.</p>
</details>

---

<h2 id="codigo-fonte">9. 💻 Código Fonte</h2>

Explore a arquitetura React completa no repositório oficial:

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=000)
[![Repositório](https://img.shields.io/badge/Repositório-Domisnnet%2FFinancial--Educator--React-61DAFB?style=for-the-badge&logo=github&labelColor=0d1117)](https://github.com/Domisnnet/Financial-Educator-React)

### Estrutura do Projeto

```text
Financial-Educator-React/
│
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── contexts/
│   ├── firebase/
│   ├── hooks/
│   ├── pages/
│   ├── services/
│   ├── utils/
│   ├── App.tsx
│   └── main.tsx
│
├── package.json
├── vite.config.ts
└── README.md
```

| Diretório | Responsabilidade |
| :--- | :--- |
| **assets/** | Imagens, ícones e arquivos estáticos. |
| **components/** | Componentes reutilizáveis. |
| **contexts/** | Gerenciamento com Context API. |
| **firebase/** | Configuração Firebase. |
| **hooks/** | Hooks customizados. |
| **pages/** | Páginas principais. |
| **services/** | Comunicação Firebase/APIs. |
| **utils/** | Funções auxiliares. |

---

<h2 id="créditos">10. 📝 Créditos & Reconhecimentos</h2>

| Atribuição | Responsável / Recurso | Descrição |
| :--- | :--- | :--- |
| **Full-Stack Dev** | **Domisnnet** | Design, arquitetura React e configuração DevOps. |
| **Infraestrutura** | **Google Firebase** | Provedor de Hosting e serviços cloud. |
| **Tecnologias** | **React / TypeScript / Vite** | Comunidades abertas pela evolução contínua. |

---

<h2 id="licenca">11. 📄 Licença</h2>

Este projeto está sob a [![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/Financial-Educator-React/blob/main/LICENSE)

---

<h2 id="perfil-do-github">12. 👨‍💻 Perfil do GitHub / Considerações</h2>

## 🌟 Considerações Finais

O **Educador Financeiro Inteligente** une tecnologia, organização e educação financeira em uma plataforma focada em jovens que estão começando a trabalhar.

Além de ajudar no controle de gastos e na criação de metas simples, o projeto oferece uma base moderna para evoluir com novos recursos, mantendo a experiência amigável, clara e objetiva.

Novas funcionalidades podem ser adicionadas para deixar a jornada financeira ainda mais prática.

Para conhecer todos os meus projetos acesse meu Repositório no GitHub:

<a href="https://github.com/Domisnnet"> 
  <img src="src/assets/images/DomisDev.png" width="90" style="border-radius: 50%" alt="Domisnnet GitHub"> 
</a>