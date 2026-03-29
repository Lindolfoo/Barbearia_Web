# 💈 Kings Barbearia — Projeto Web

Site institucional de barbearia desenvolvido como atividade extra da NP1.

## 📁 Estrutura do Projeto

```
barbearia/
├── index.html              ← Página inicial (Home)
├── style.css           ← CSS externo único (Mobile First)
└── pages/
    ├── servicos.html       ← Serviços e tabela de preços
    ├── equipe.html         ← Equipe de barbeiros
    ├── agendamento.html    ← Formulário de agendamento
    └── contato.html        ← Contato, mapa e redes sociais
```

## ✅ Requisitos Atendidos

### 1. Elementos HTML Básicos
- `<img>` — logo no header, fotos dos serviços, barbeiros e galeria
- `<ul>` — menu de navegação, footer, lista de diferenciais, redes sociais
- `<ol>` — passos do agendamento (página agendamento.html)
- `<table>` — tabela de preços (servicos.html), tabela de barbeiros (equipe.html), tabela de contato (contato.html)

### 2. Navegação e Links
- **Links internos**: menu de navegação entre todas as páginas do projeto
- **Links externos**: Instagram, Facebook, TikTok, WhatsApp (target="_blank")

### 3. Folhas de Estilo — CSS Externo
- Todo o CSS está em `css/style.css`
- Nenhum uso de `style=""` inline ou `<style>` interno

### 4. Variáveis CSS (Custom Properties)
```css
:root {
  --cor-fundo:         #0a0a0a;
  --cor-fundo-2:       #111111;
  --cor-fundo-3:       #1a1a1a;
  --cor-dourado:       #c9a84c;
  --cor-dourado-claro: #e2c97e;
  --cor-dourado-escuro:#8a6e2a;
  --cor-texto:         #e8e8e8;
  --cor-texto-suave:   #999999;
  --cor-branco:        #ffffff;
  --cor-borda:         #2a2a2a;
  /* + variáveis de fonte, sombra, transição e borda */
}
```

### 5. Arquitetura Mobile First
- Todo CSS base escrito para smartphones (telas pequenas)
- Layout evolui apenas via `@media (min-width: ...)`

### 6. Media Queries — 4 Breakpoints
| Breakpoint | Tamanho |
|---|---|
| 480px | Smartphones maiores |
| 768px | Tablets |
| 1024px | Laptops |
| 1200px | Desktops grandes |

### 7. Sistemas de Layout
- **Flexbox**: header, menu de navegação, hero, botões, cards de contato, footer, redes sociais
- **CSS Grid**: grade de serviços, grade de barbeiros, galeria de fotos, footer

### 8. Unidades de Medida
- **Absolutas**: `px` para bordas, tamanhos fixos, `max-width`
- **Relativas**: `rem` para tipografia e espaçamentos, `%` e `vw` para larguras, `vh` para hero

## 🎨 Design
Inspirado nos sites **Barbearia Corleone** e **Feel King Barbearia**.
- Tema escuro premium (preto + dourado)
- Tipografia serif + sans-serif condensado
- Mobile First responsivo
- Hover states e transições suaves

## 🚀 Como Usar
1. Clone o repositório
2. Abra `index.html` no navegador
3. Navegue entre as páginas pelo menu

---
*Desenvolvido para atividade extra NP1 — 30/03/2026*
