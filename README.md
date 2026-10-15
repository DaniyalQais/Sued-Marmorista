# Sued Marmorista — Website Institucional

Website conceitual e demonstrativo de alto padrão desenvolvido para a **Sued Marmorista** (Fortaleza — CE), especialista em bancadas, ilhas, pias esculpidas, escadas e superfícies nobres em mármores, granitos, quartzo, pedras sintéticas e Dekton.

---

## 🌟 Características

- **Design Premium & Arquitetônico**: Paleta sofisticada em tons de pedra natural, off-white, grafite e toques em laranja da marca.
- **Hero Responsivo**: Layout de duas colunas no desktop e fotografia em tela cheia com overlay sutil no mobile.
- **Tipografia Refinada**: Combinação elegante com *Fraunces* (títulos clássicos) e *Instrument Sans* (interface contemporânea).
- **Galeria de Materiais**: Amostras detalhadas de Mármore, Granito, Quartzo, Pedras Sintéticas e Dekton.
- **Galeria de Projetos**: Apresentação de cozinhas, cubas esculpidas, escadas, bancadas gourmet e painéis.
- **Jornada de Contato Direta**: Botões e botão flutuante integrados diretamente ao WhatsApp com mensagem pré-preenchida em português.
- **Totalmente Responsivo**: Otimizado para visualização em 375px, 390px, 430px, 768px, 1024px e 1440px+.

---

## 📁 Estrutura do Projeto

```text
├── index.html            # Estrutura HTML5, estilos CSS e scripts
├── assets/               # Imagens fotográficas e amostras de materiais
│   ├── hero.jpg
│   ├── mat-marmore.jpg
│   ├── mat-granito.jpg
│   ├── mat-quartzo.jpg
│   ├── mat-sintetica.jpg
│   ├── mat-dekton.jpg
│   ├── proj-cozinha.jpg
│   ├── proj-banheiro.jpg
│   ├── proj-escada.jpg
│   ├── proj-bancada.jpg
│   └── proj-outros.jpg
└── README.md
```

---

## 🚀 Como Executar Localmente

Você pode abrir diretamente o arquivo `index.html` em qualquer navegador moderno ou rodar um servidor local leve:

### Via Python:
```bash
python -m http.server 8080
```
Depois acesse `http://localhost:8080` no navegador.

### Via Node.js:
```bash
npx serve .
```

---

## ⚙️ Configuração do WhatsApp

No final de `index.html`, o número e a mensagem padrão podem ser ajustados na variável central:

```javascript
var CLIENT_CONFIG = {
  whatsappNumber: "558585930000",
  whatsappMessage: "Olá! Gostaria de solicitar um orçamento para o meu projeto com a Sued Marmorista."
};
```

---

## 📄 Licença

Projeto desenvolvido para fins demonstrativos e conceituais.
