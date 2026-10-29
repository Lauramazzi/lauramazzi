# Olá, eu sou a Laura Mazzi! 👋

Estudante de **Engenharia de Computação** com formação prévia em **Processos Gerenciais**. Construo soluções com IA de ponta a ponta para negócios reais: entendo o processo, desenho o fluxo, integro os sistemas e coloco no ar.

📍 São Carlos/SP · 🌐 [Portfólio e currículo](https://portfolio-laura-mazzi.vercel.app/) · 💼 [LinkedIn](https://linkedin.com/in/laura-mazzi-90b8a4210) · ✉️ [lbmazzi98@gmail.com](mailto:lbmazzi98@gmail.com)

---

## 🤖 IA aplicada

### 👁️ [Lash Studio — Agente de IA + Agendamento](https://github.com/Lauramazzi/lash-agendamento-anamnese) · [🌐 Testar online](https://lash-studio-agendamento.netlify.app/)
Sistema em produção para um estúdio de cílios, com um **agente de IA (Gemini Vision)** que analisa a foto dos olhos da cliente, ranqueia os formatos de extensão mais indicados e mostra uma simulação visual antes do atendimento.
- Agente com arquitetura **BDI** (crenças → desejos → intenções) e base de conhecimento de formatos
- Chamadas ao Gemini por **função serverless** (Netlify Functions), sem expor a chave de API
- Agendamento autônomo, anamnese digital e painel administrativo com **Firebase** e regras de segurança no Firestore
- [Plano de evolução para SaaS multi-tenant](https://github.com/Lauramazzi/lash-agendamento-anamnese/blob/main/saas_transformation_report.md)

### 📡 [Radar de Avaliações — triagem de avaliações com IA](https://github.com/Lauramazzi/radar-avaliacoes) · [🌐 Dashboard](https://lauramazzi.github.io/radar-avaliacoes/)
Automação no **Make** que classifica avaliações de delivery com **IA (Gemini)** e destaca os casos que exigem ação imediata, como alimento estragado ou alergênico servido a quem avisou ter alergia.
- Webhook → Make → Gemini com **saída em JSON Schema** (sentimento, categoria, gravidade, resumo e resposta sugerida) → data store → dashboard
- Regras de gravidade escritas no prompt e **resultado revisado** nas 30 avaliações de teste, com o erro encontrado documentado
- Fluxo montado com a API do Claude e migrado para o Gemini trocando só o módulo da chamada

---

## ⚙️ Automações e ferramentas internas

| Projeto | Problema resolvido | Stack | Acesso |
|---|---|---|---|
| [**Rotas — Oficinas e Costureiras**](https://github.com/Lauramazzi/rotas-demo) | Roteirização de coletas e motoristas integrada ao WhatsApp e Google Sheets | JavaScript, Google Apps Script | [🌐 Demo](https://lauramazzi.github.io/rotas-demo/) |
| [**Painel de Estoque Omie**](https://github.com/Lauramazzi/painel-estoque-demo) | Visão do estoque por depósito físico direto da API do ERP Omie, com leitura de CSV | JavaScript, API REST Omie | [🌐 Demo](https://lauramazzi.github.io/painel-estoque-demo/) |
| [**Abastecimento de Linhas**](https://github.com/Lauramazzi/abastecimento-linhas) | Controle de pallets e abastecimento das linhas de produção pelo celular | HTML/JS, Google Sheets | [🌐 Demo](https://lauramazzi.github.io/abastecimento-linhas/) |
| [**Controle de Veículo**](https://github.com/Lauramazzi/controle-veiculo) | Registro de uso e manutenção de veículo | HTML/JS | [🌐 Demo](https://lauramazzi.github.io/controle-veiculo/controle_veiculo_1.html) |

## 📊 Dashboards e gestão

| Projeto | Problema resolvido | Stack | Acesso |
|---|---|---|---|
| [**Barbearia — Dashboard financeiro**](https://github.com/Lauramazzi/barbearia) | Consolida relatórios do AppBarber com despesas, parcelas, caixa e metas mensais | Python, Streamlit, Pandas | Código |
| [**Heloísa Mazzi — App financeiro (PWA)**](https://github.com/Lauramazzi/heloisa-mazzi) | Registro de saídas, vencimentos, reserva e fechamento do mês pelo celular | JavaScript, PWA | [🌐 App](https://heloisa-mazzi.vercel.app) |
| [**Controle Financeiro**](https://github.com/Lauramazzi/controle-financeiro) | Controle financeiro pessoal | Python, Streamlit | Código |

## 🌐 Sites e páginas de venda

[Mazzi Serviços](https://lauramazzi.github.io/mazzi-servicos/) · [RK Refrigeração](https://lauramazzi.github.io/rk-refrigeracao-site/) · [Marmitas da Semana](https://lauramazzi.github.io/Marmita-ebook/)

---

## 🛠️ Tecnologias

- **IA:** Gemini API (Vision e saída estruturada), engenharia de prompt, agentes de IA
- **Automação:** Make (webhooks, data stores, cenários)
- **Linguagens:** JavaScript (ES6+), Python, Java, C#, PHP (Laravel)
- **Dados:** Streamlit, Pandas, Power BI, Google Sheets / Apps Script
- **Backend e nuvem:** Firebase (Firestore, Auth, Cloud Functions), Netlify Functions, APIs REST
- **Negócio:** ERP Omie, PDCA, melhoria contínua de processos, metodologias ágeis
- **Deploy:** Git/GitHub, GitHub Pages, Netlify, Vercel

---
*Foco em criar códigos funcionais que resolvem problemas reais.*
