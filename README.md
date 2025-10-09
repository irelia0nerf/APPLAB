🚀 Prompt Generator Pro

**Geração de Documentação Técnica com IA + Google Drive + Pesquisa na Web**  
Criado por [Alex Bolson](https://g.dev/alexbolsonfounder) – Founder da [FoundLab.Cloud](https://foundlab.cloud) e Arquiteto da Umbrella, maior infraestrutura de reputação e compliance-as-a-service da América Latina. Membro do ecossistema [Google Developers](https://g.dev/alexbolsonfounder).

---

## 🧠 O que é

**Prompt Generator Pro** é uma plataforma inteligente para gerar conteúdo técnico profissional com base em:

- Arquivos pessoais do Google Drive
- Pesquisa contextual automática na web
- Estruturas pré-configuradas para entregas técnicas reais
- Inteligência artificial com refinamento interativo

A ferramenta automatiza e eleva a produção de documentos técnicos como whitepapers, APIs, propostas, documentação, entre outros — tudo com exportação multi-formato e integração direta com Google Cloud.

---

## ⚙️ Funcionalidades

- 🔐 Login com Google OAuth2
- 📂 Integração com Google Drive (leitura de arquivos contextuais)
- 🌐 Busca automatizada via Google Custom Search API
- 🧠 Geração de prompts com base em tipo de entrega
- ♻️ Sistema de refinamento (retry + ajuste de nível de detalhe)
- 🖥️ Visualização em raw + markdown renderizado
- 💾 Exportação em `.md`, `.html`, `.pdf`, `.zip`
- ☁️ Upload automático para o Google Drive

---

## 📁 Tipos de entrega suportados

- 📄 Whitepaper técnico  
- 🔷 Blueprint de projeto para GitHub  
- 📚 Documentação técnica  
- 🔌 Documentação de API (REST/OpenAPI)  
- 🏗️ Documento de Arquitetura  
- 💼 Proposta de Projeto Técnico  
- 🔍 Estudo de Caso (Case Study)  
- 📖 README Profissional

---

## 📦 Estrutura do Projeto

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

---

## 🛠️ Instalação

```bash
npm install
npm start


⸻

🔑 Configuração

Google OAuth2
	1.	Acesse Google Cloud Console
	2.	Crie um novo projeto e ative a Google Drive API
	3.	Vá em APIs & Services → Credentials → Create Credentials → OAuth client ID
	4.	Tipo: Web Application
	5.	Adicione este redirect URI:

http://localhost:3000

	6.	Copie o Client ID e substitua no App.tsx:

<GoogleAuth clientId="SEU_CLIENT_ID.apps.googleusercontent.com" onToken={setGoogleToken} />


⸻

Google Custom Search API
	1.	Vá para Google Programmable Search Engine
	2.	Crie um search engine para toda a web
	3.	Copie o CX ID
	4.	Crie uma API Key no Google Cloud Console
	5.	No projeto, crie um arquivo .env com:

REACT_APP_GOOGLE_SEARCH_KEY=YOUR_GOOGLE_API_KEY
REACT_APP_GOOGLE_SEARCH_CX=YOUR_CX_ID

	6.	Reinicie o servidor:

npm start


⸻

📜 Licença

MIT — Livre para uso e modificação.

⸻

📞 Contato

Desenvolvido por Alex Bolson
🔗 Founder da FoundLab.Cloud
📩 Disponível para licenciamento, parcerias ou aquisição comercial

⸻


---