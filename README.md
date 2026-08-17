# 📚 EduReader

**EduReader** (anteriormente PageKeeper) é um leitor web de PDF e EPUB com estética premium Vibe Coding (Glassmorphism, Dark Mode) desenhado para educação. Ele possui biblioteca local persistente, sincronização via WebDAV, anotações e suporte offline nativo.

## 🎯 Project Goal
Oferecer uma experiência de leitura imersiva, moderna e rápida para alunos e professores. Todo o processamento e armazenamento ocorrem no próprio dispositivo para máxima privacidade, e a interface foi aprimorada com animações, fontes premium (Inter/Outfit) e dark mode focado no conforto visual.

## 🛠 Tech Stack
- **Frontend Core:** HTML5, CSS3, Vanilla JavaScript.
- **Styling:** CSS puro com variáveis dinâmicas e injeção do TailwindCSS (CDN) para utilitários, e estética Glassmorphism.
- **Tipografia:** Google Fonts (Outfit e Inter).
- **Armazenamento Local:** IndexedDB (para PDFs, EPUBs e dados).
- **Bibliotecas:** PDF.js (Mozilla) e ePub.js.
- **PWA:** Service Workers para uso 100% offline.

## 🚀 Setup & Run Instructions
Como o EduReader é uma aplicação web estática, não há processos de build ou dependências do Node complexas.
1. Abra a pasta do projeto e inicie um servidor HTTP local:
   ```bash
   npx serve .
   # ou
   python -m http.server 3000
   ```
2. Acesse `http://localhost:3000` em seu navegador.

## 🌐 Deployment URL
Pronto para ser hospedado no GitHub Pages, Cloudflare Pages, Netlify ou Vercel. 
- **Para GitHub Pages:** Simplesmente faça um push da branch `main` e ative o GitHub Pages servindo do `/(root)`.
- Recomenda-se utilizar Cloudflare Pages (sua preferência) pela facilidade de arrastar a pasta do projeto.

## 📝 Changelog / History of Modifications
- **v1.0 (Refatoração Vibe Coding):** 
  - Fork do PageKeeper original.
  - Renomeado para EduReader em todas as referências (UI, Service Workers, Logs).
  - Adição de TailwindCSS via CDN para agilizar layouts.
  - Injeção de tipografia premium (Inter e Outfit).
  - Refatoração do Dark Mode (`[data-tema="oscuro"]`) para usar gradientes modernos e Glassmorphism.
  - Otimização das animações nos cards da biblioteca e botões laterais.
