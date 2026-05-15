# Money ✦

Controle financeiro pessoal, feito com React + JSX rodando direto no browser — sem instalação, sem servidor, sem dependências externas além de CDN.

Acesse em: **[leonzmarina.github.io/plannerfinanceiro](https://leonzmarina.github.io/plannerfinanceiro)**

---

## ✨ Funcionalidades

- **Registrar gastos e entradas** com descrição, valor, data e categoria
- **Resumo** com totais, saldo, gauge de orçamento, pizza por categoria, top 5 gastos e evolução mensal
- **Lançamentos** com filtro por tipo, intervalo de datas e gráfico mensal
- **Perfil** com nome e foto, salvos localmente
- **Exportar dados** em CSV, Excel e PDF (relatório minimalista preto e branco)
- **2 temas** que respondem automaticamente ao modo escuro/claro do celular:
  - ✿ **Bloom** — rosa vibrante, estilo dashboard moderno
  - ◆ **Obsidian** — escuro estilo admin dashboard
- **PT 🇧🇷 e EN 🇺🇸** — troca de idioma sem perder os dados das categorias
- **Dados 100% locais** — tudo salvo no `localStorage`, nenhuma informação vai a servidores
- **PWA-ready** — adicione como atalho na tela inicial do celular

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| **React 18** | Interface com hooks (`useState`, `useMemo`, `useEffect`) |
| **JSX** | Compilado no browser via Babel Standalone |
| **SVG** | Gráficos gauge, pizza, barras e linha desenhados do zero |
| **localStorage** | Dados, tema, idioma e perfil persistidos localmente |
| **GoatCounter** | Analytics minimalista, sem cookies |
| **Google Fonts** | Cormorant Garamond · DM Sans |

Zero bundlers. Zero frameworks de CSS. Zero backend.

---

## 📁 Estrutura

```
plannerfinanceiro/
└── index.html   # app inteiro em um único arquivo
```

---

## 📱 Como usar no celular

**iPhone (Safari)**
1. Abra o link no Safari
2. Toque em Compartilhar → "Adicionar à Tela de Início"

**Android (Chrome)**
1. Abra o link no Chrome
2. Menu → "Adicionar à tela inicial"

Vai aparecer como ícone na home, igual a um app nativo.

---

## 🔒 Privacidade

O código-fonte é público, mas **os seus dados são privados**. Tudo fica salvo apenas no `localStorage` do seu próprio dispositivo. Nenhuma informação é enviada para servidores — exceto contagem anônima de visitas via GoatCounter (sem cookies, sem dados pessoais).

---

## 🚀 Deploy no GitHub Pages

1. Faça fork ou crie um repositório
2. Faça upload do `index.html` como arquivo principal
3. Vá em **Settings → Pages → Branch: main → Save**
4. Aguarde 1–2 minutos

---

## 📂 Categorias

**Gastos:** Alimentação · Mercado · Transporte · Saúde · Lazer · Moradia · Educação · Roupas · Beleza · Serviços · Outros

**Entradas:** Salário · Freelance · Bônus · Presente · Investimentos · Aluguel · Reembolso · Outros

---

feito com 🩷 por [@marinnaleon](https://www.tiktok.com/@marinnaleon)

[![TikTok](https://img.shields.io/badge/TikTok-@marinnaleon-black?logo=tiktok)](https://www.tiktok.com/@marinnaleon)
[![GitHub](https://img.shields.io/badge/GitHub-leonzmarina-181717?logo=github)](https://github.com/leonzmarina)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-marinamleon-0A66C2?logo=linkedin)](https://linkedin.com/in/marinamleon)
