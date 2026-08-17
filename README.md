<div align="center">
  <img src="iconos/icono.svg" width="150" alt="EduReader Logo">
  <h1>📖 EduReader</h1>
  <p><b>Leitor de Livros Eletrônicos (Web/PWA) – Vibe Coding Edition</b></p>
  <p>
    <a href="https://github.com/zonaeducacional">Desenvolvido e Refatorado por Sérgio Araújo</a> •
    <a href="https://educacion.bilateria.org/">Projeto Original de Juan José de Haro</a>
  </p>
</div>

<br>

O **EduReader** é um aplicativo web progressivo (PWA) de ponta projetado para rodar offline e em qualquer dispositivo moderno. Esta **Vibe Coding Edition** traz uma refatoração completa com foco em uma interface *Glassmorphism Azul Profundo*, animações sutis e foco absoluto na experiência e legibilidade para estudantes e professores.

## ✨ Destaques & Funcionalidades

- **Design Premium "Vibe Coding"**: Uma interface incrivelmente fluida que adota transparência *Glassmorphism*, cores vibrantes (Azul Oceânico & Amarelo) e Modo Escuro imersivo, contrastando perfeitamente a leitura noturna ou diurna.
- **Suporte Robusto de Arquivos**: Abra instantaneamente seus livros nos formatos **EPUB**, **PDF** e até mesmo histórias em quadrinhos digitais (**CBZ/CBR**).
- **Integração com a Nuvem**: Sincronize arquivos através de servidores WebDAV para não perder o fio da meada entre os estudos.
- **100% Offline (PWA)**: Pode ser instalado direto pelo navegador no desktop ou smartphone (Android/iOS) rodando inteiramente offline graças aos *Service Workers*.
- **Controle de Leitura e Estatísticas**: Salva onde você parou, marcações, e calcula o tempo dedicado a cada livro!

## 🚀 Como Rodar o Projeto

### Rodando Localmente
1. Certifique-se de que tenha o `python` instalado na sua máquina (Debian GNU/Linux).
2. Pelo terminal, vá para a pasta raiz do projeto:
   ```bash
   cd edu-reader
   python3 -m http.server 3000
   ```
3. Abra o navegador em `http://localhost:3000`.

### Hospedando Online (Cloudflare Pages ou GitHub Pages)
Sendo um projeto puramente *Vanilla JS* e *Web Estático*, você não precisa de rotinas de Build complicadas. 
Basta dar push (enviar) a branch `main` diretamente para a Cloudflare Pages, Vercel, ou hospedar pelo próprio [GitHub Pages](https://pages.github.com/).
A configuração do `sw.js` vai automaticamente habilitar seu site como um aplicativo instalável!

## 🛠️ Tecnologias Utilizadas

- **Core**: Vanilla JavaScript (ES6 Modules), HTML5 Semântico e CSS3 puro.
- **Visual & Estilização**: TailwindCSS + Design System de CSS modular com tipografia moderna (`Inter` e `Outfit`).
- **Renderização e Parsing de Livros**: 
  - `pdf.js` para PDF
  - `epub.js` para ePub
  - `JSZip` para CBZ
  - `MathJax` para fórmulas matemáticas
- **Iconografia**: Lucide Icons.

## 🤝 Créditos

O **EduReader** foi meticulosamente redesenhado (Design, Estilos e Experiência do Usuário) por **Sérgio Araújo**, inspirado na arquitetura sólida original do projeto Open Source (*PageKeeper*) construído pelo acadêmico Juan José de Haro. 

## 📝 Licença

Sob a licença **MIT License** – sinta-se livre para usar e modificar, garantindo os devidos créditos aos desenvolvedores e ferramentas!
