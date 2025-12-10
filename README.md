# 🏫 Correção: Landing Page EducaFuturo

Este repositório contém a **resolução/gabarito** do exercício de fixação proposto na Unidade Curricular de **Programação Client-Side** (HT-SIS-02-N-25-12910).

> **Professor:** Daniel Ventura de Almeida  
> **Tema:** Estruturação HTML5 e Estilização CSS (Layout & Posicionamento)

---

## 🎯 Objetivo do Projeto

Desenvolver a página principal ("One Page") para a escola de tecnologia fictícia **EducaFuturo**. O foco é consolidar conhecimentos em:
- **Layout:** Flexbox e CSS Grid.
- **Posicionamento:** Fixed, Relative, Absolute e Sticky.
- **Unidades:** `vh`, `%`, `fr`.

---

## 📋 Requisitos Implementados

Abaixo estão os requisitos solicitados no exercício e aplicados nesta correção:

### 1. Configuração Inicial 🛠️
- [x] Estrutura de pastas criada (`projeto-educafuturo/` contendo `index.html` e `css/style.css`).
- [x] Reset CSS básico aplicado para remover margens padrão e definir `box-sizing: border-box`.

### 2. Cabeçalho (Header) 🧭
**Conceitos:** `position: fixed`, `display: flex`, `z-index`.
- [x] Tag `<header>` com altura fixa e cor de fundo sólida.
- [x] Elemento fixo no topo da página.
- [x] Layout Flexbox para separar Logo (esquerda) e Menu (direita) (`justify-content: space-between`).
- [x] Menu de navegação (`<nav>`) com links para: Home, Cursos, Sobre, Contato.

### 3. Seção "Home" (Capa) 🏠
**Conceitos:** `vh`, `flex-direction`, alinhamento.
- [x] Seção com altura de `100vh` (tela cheia).
- [x] Conteúdo centralizado verticalmente e horizontalmente usando Flexbox.
- [x] Elementos (Título, Subtítulo, Botão) empilhados via `flex-direction: column`.

### 4. Seção "Cursos" (Vitrine) 📚
**Conceitos:** `display: grid`, `gap`, `1fr`.
- [x] Altura mínima de `100vh`.
- [x] Container utilizando **CSS Grid**.
- [x] Divisão em 3 colunas iguais (`grid-template-columns: 1fr 1fr 1fr` ou `repeat(3, 1fr)`).
- [x] Espaçamento (`gap`) de 20px entre os cards.

### 5. Seção "Sobre" (Destaque) ℹ️
**Conceitos:** `position: relative` vs `position: absolute`.
- [ ] Card centralizado na tela.
- [ ] Uso de `position: relative` no container do card.