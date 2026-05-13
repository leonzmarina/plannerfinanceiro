# 💸 Money

Controle financeiro pessoal minimalista, feito com React + JSX rodando direto no browser (sem instalação, sem servidor, sem dependências externas além de CDN).

Acesse em: **[marinnaleon.github.io/plannerfinanceiro](https://leonzmarina.github.io/plannerfinanceiro/)**

---

## ✨ Funcionalidades

- **Registrar gastos e entradas** com descrição, valor, data e categoria
- **Dashboard** com totais, saldo do período, gráfico gauge de orçamento e pizza por categoria
- **Lançamentos** com filtro por tipo e intervalo de datas
- **Filtro de data** customizável (de/até) em todas as abas
- **2 temas visuais** alternáveis diretamente no app:
  - 🌸 **Rosé** — paleta feminina em tons de rosa e verde-sage
  - ◼ **Mono** — minimalista neutro com tipografia Space Mono
- **Dados 100% locais** — tudo salvo no `localStorage` do seu dispositivo, nenhuma informação vai para servidores
- **PWA-ready** — pode ser adicionado como atalho na tela inicial do celular

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| **React 18** | Interface declarativa com hooks (`useState`, `useMemo`) |
| **JSX** | Compilado no browser via Babel Standalone |
| **SVG** | Gráficos gauge e pizza desenhados à mão, sem bibliotecas |
| **localStorage** | Persistência de dados e preferência de tema |
| **Google Fonts** | Cormorant Garamond · DM Sans · Space Mono |

Zero bundlers. Zero frameworks de CSS. Zero backend.

---

## 📁 Estrutura

```
money/
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

O código-fonte é público, mas **os seus dados são privados**. Tudo fica salvo apenas no `localStorage` do seu próprio dispositivo. Nenhuma informação é enviada para nenhum servidor.

---

## 🚀 Deploy no GitHub Pages

1. Faça fork ou crie um repositório chamado `plannerfinanceiro`
2. Faça upload do `index.html` como arquivo principal
3. Vá em **Settings → Pages → Branch: main → Save**
4. Aguarde 1–2 minutos — seu app estará em `https://seu-usuario.github.io/plannerfinanceiro`

---

## 📂 Categorias disponíveis

**Gastos:** Alimentação · Mercado · Transporte · Saúde · Lazer · Moradia · Educação · Roupas · Beleza · Serviços · Outros

**Entradas:** Salário · Freelance · Bônus · Presente · Investimentos · Aluguel · Reembolso · Outros

---

feito com 🩷 por [@marinnaleon](https://www.tiktok.com/@marinnaleon)

[![TikTok](https://img.shields.io/badge/TikTok-@marinnaleon-black?logo=tiktok)](https://www.tiktok.com/@marinnaleon)
[![GitHub](https://img.shields.io/badge/GitHub-leonzmarina-181717?logo=github)](https://github.com/leonzmarina)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-marinamleon-0A66C2?logo=linkedin)](https://linkedin.com/in/marinamleon)
