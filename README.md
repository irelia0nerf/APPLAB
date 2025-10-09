<div align="center">
  <img src="https://foundlab.cloud/assets/umbrella-logo.png" alt="Prompt Generator Pro" width="120">
  <h1>🚀 Prompt Generator Pro</h1>
  <strong>Geração Automática de Documentação Técnica com IA, Google Drive e Web Search</strong>
  <br>
  <a href="https://foundlab.cloud">by Alex Bolson • Founder da FoundLab.Cloud</a>
</div>

---

## 🧠 Sobre

**Prompt Generator Pro** é a plataforma definitiva para criar conteúdo técnico de altíssimo nível, integrando:

- **Arquivos do Google Drive**
- **Pesquisa Web Automática**
- **Estruturas Profissionais para Blueprints, APIs, Whitepapers**
- **Inteligência Artificial de última geração (Gemini/GPT)**

Tudo plugado num fluxo só: do briefing ao Markdown, PDF ou ZIP pronto para auditar e publicar.

---

## ⚡️ Por que usar

- **Automatize toda a produção de documentação técnica**
- Gere whitepapers, blueprints, APIs e propostas em minutos
- Use dados reais do seu Google Drive + contexto da web
- Refinamento interativo: ajuste nível de detalhe na hora
- Exporte em `.md`, `.html`, `.pdf` e `.zip` em 1 clique
- Integração nativa com Google Cloud — pronto pra times ágeis, squads, consultorias e startups

---

## 🚀 Funcionalidades

- 🔒 **Login seguro via Google OAuth2**
- 📂 **Integração instantânea com Google Drive**
- 🌐 **Busca automática via Google Custom Search API**
- 🧠 **Geração de prompts e documentação baseada em tipos reais de entrega**
- 🔄 **Refinamento automático (retry, ajuste de detalhamento)**
- 🖥️ **Visualização em raw e Markdown renderizado**
- 💾 **Exportação fácil pra diversos formatos**
- ☁️ **Upload direto para sua conta Google Drive**

---

## 📁 Tipos de Entrega

- Whitepaper técnico institucional
- Blueprint de projeto para GitHub
- Documentação técnica
- Documentação de API (REST/OpenAPI)
- Documento de Arquitetura
- Proposta de Projeto Técnico
- Estudo de Caso (Case Study)
- README Profissional

---

## 🛠️ Instalação Rápida

```bash
git clone https://github.com/seuuser/prompt-generator-pro.git
cd prompt-generator-pro
npm install
npm start
```

---

## 🔑 Configuração

### Google OAuth2

1. Acesse [Google Cloud Console](https://console.cloud.google.com/).
2. Crie um novo projeto e ative a Google Drive API.
3. Em **APIs & Services > Credentials > Create Credentials > OAuth client ID**:
   - Tipo: Web Application
   - Redirect URI: `http://localhost:3000`
4. Cole o Client ID em `App.tsx`:

```tsx
<GoogleAuth clientId="SEU_CLIENT_ID.apps.googleusercontent.com" onToken={setGoogleToken} />
```

---

### Google Custom Search API

1. Crie um search engine em [Programmable Search Engine](https://programmablesearchengine.google.com/).
2. Copie o CX ID.
3. Gere uma API Key no Google Cloud Console.
4. Crie o arquivo `.env`:

```
REACT_APP_GOOGLE_SEARCH_KEY=YOUR_GOOGLE_API_KEY
REACT_APP_GOOGLE_SEARCH_CX=YOUR_CX_ID
```
5. Reinicie o servidor:

```bash
npm start
```

---

## 💼 Licenciamento & Serviços

MIT.  
**Disponível para licenciamento, parceria ou setup personalizado** (consultoria, deploy, treinamento, white-label).  
Fala direto: [alex@foundlab.cloud](mailto:alex@foundlab.cloud) ou [LinkedIn](https://g.dev/alexbolsonfounder).

---

## 👨‍💻 Estrutura do Projeto

```text
prompt-generator-pro/
├─ package.json
├─ tsconfig.json
├─ public/
│  └─ index.html
└─ src/
   ├─ index.tsx
   ├─ App.tsx
   ├─ hooks/
   │   ├─ useGoogleDrive.ts
   │   └─ useGoogleSearch.ts
   └─ components/
       ├─ GoogleAuth.tsx
       ├─ ReferenceSelector.tsx
       └─ PromptGenerator.tsx
```

---

## 🧩 Roadmap

- [x] Integração Google Drive
- [x] Pesquisa Web com API
- [x] Exportação multi-formato
- [x] Estruturas de entrega profissional
- [ ] Deploy cloud/serverless
- [ ] Templates visuais customizados
- [ ] White-label para consultorias

---

## 🤝 Contato & Parcerias

Criado por **Alex Bolson** — Founder da [FoundLab.Cloud](https://foundlab.cloud)  
Google Developers Ecosystem  
Disponível para licenciamento, parceria, treinamento ou aquisição institucional.

[Site](https://foundlab.cloud) | [LinkedIn](https://g.dev/alexbolsonfounder) | [E-mail](mailto:alex@foundlab.cloud)

---

<div align="center">
  <b>Pronto pra automatizar sua documentação? <a href="mailto:alex@foundlab.cloud">Entre em contato agora</a> e feche o setup express.</b>
</div>