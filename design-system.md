---
title: Twisty - Minimalist Design System (Gestão SLA)
description: Padrões de interface para refatoração baseada em Minimalismo e Soft Glassmorphism 
---

# Design System - SLA "Twisty" Aesthetic

Uma bússola visual para a remontagem do frontend da aplicação de SLA Mestre, baseada estritamente na referência enviada pelo usuário. O foco principal está na leveza visual, amplos raios de borda e forte hierarquia de tipografia.

## 1. Tokens Estruturais (Layout)
A base principal do site troca a austeridade de contrastes agressivos por respiração e "flutuação" dos componentes. 

- **Fundo Principal (App):**  `bg-[#f0f2f5]` ou `bg-slate-50` (Traz conforto ocular para longos períodos de trabalho e destaca a pureza branca dos gráficos e tabelas).
- **Cards Principais & Modais:** `bg-white shadow-[0_8px_30px_rgb(0,0,0,0.04)] rounded-3xl border border-gray-100`
- **Tabelas / Áreas Lisas:** Deixam de lado grids óbvios em prol de listas divididas levemente por `border-b border-gray-100/50`.

## 2. Tipografia (Inter Serifless)
Tudo girará em torno de variações contrastantes de peso e dimensão. Textos mutos serão minúsculos, negritados e opacos, e os focais muito fortes e limpos.

- **Títulos / Headers (ex: Your Recent Projects):** `text-lg font-bold text-slate-800 tracking-tight`
- **Labels (ex: This week's income):** `text-[10px] font-medium text-slate-400 leading-relaxed`
- **Valores Gigantes (ex: +20% / SLA):** `text-4xl font-black text-slate-900`

## 3. Botões & Badges (As Pílulas)
O coração da reestilização. Removemos os botões quadrados do bootstrap style e vamos abraçar completamente os elementos longos de pílula.

| Componente | Classes Essenciais | Exemplo de Aplicação |
| :--- | :--- | :--- |
| **Ação Principal** (Ex: Salvar, Cadastrar) | `bg-slate-900 text-white rounded-full font-semibold hover:bg-slate-800 transition-all` | Botão final nos forms |
| **Ação Neutra** (Ex: Excel, PDF, Filtro) | `bg-white border border-gray-200 text-slate-700 rounded-full shadow-sm hover:shadow-md hover:border-gray-300 font-medium transition-all` | Operações da Tabela Mestra |
| **Badges Inline** (Ex: Pago, Cancelado) | `bg-slate-100 text-slate-600 rounded-full px-3 py-1 text-[10px] font-bold` | Status Finalizado |
| **Alertas Leves** (Ex: Atraso +60) | `bg-red-50 text-red-600 border border-red-100 rounded-full px-3 py-1 font-bold` | Cores de Status de SLA |

## 4. Inputs & Interatividade
Inputs devem perder as bordas chamativas azuis e assumir transparência e bordas grossas, limpas:
- **Campos Soltos (Busca):** `bg-white border-2 border-transparent focus:border-gray-200 outline-none rounded-full`
- **Campos de Formulário:** `bg-gray-50 border border-gray-200 rounded-xl focus:bg-white focus:ring-4 ring-slate-100 outline-none`
