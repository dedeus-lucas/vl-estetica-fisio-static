# VL Estética & Fisioterapia – Static Frontend Landing Page

---

# 🇧🇷 PT-BR

## 📌 Sobre o projeto

Este projeto consiste na versão **frontend estática institucional** da landing page da clínica **VL Estética & Fisioterapia**.

O foco desta aplicação é fornecer uma experiência moderna, responsiva, performática e acessível, utilizando exclusivamente tecnologias frontend.

Esta versão foi desenvolvida para deploy estático via GitHub Pages e serve como base visual independente da futura aplicação backend.

---

## 🎯 Objetivos

- Criar uma landing page moderna e responsiva
- Garantir alta performance e carregamento rápido
- Estruturar CSS modular e escalável
- Implementar UX fluida com animações suaves
- Facilitar conversão via contato direto
- Manter arquitetura frontend limpa e reutilizável

---

## 🧱 Arquitetura do projeto

A estrutura de pastas segue padrão **SMACSS** (Scalable and Modular Architecture for CSS) para separação clara de responsabilidades e manutenção escalável.

> 📌 A estrutura visual completa está documentada no print da arquitetura do projeto.

![Arquitetura do Projeto](./assets/docs/structure.png)

### Organização geral

- `/css`
  - **base/** (reset, variables, typography, globals) — Fundação e design tokens
  - **layout/** (header, hero, sections, footer) — Estrutura macro da página
  - **components/** (buttons, cards, slider, testimonials) — Componentes reutilizáveis
  - **utilities/** (containers) — Helpers e utilidades

- `/js`
  - **main.js** — lógica global, menu mobile, scroll spy
  - **slider.js** — carrossel automático de serviços

- `/assets`
  - **img/** — imagens otimizadas WebP
  - **icons/** — ícones SVG
  - **fonts/** — tipografias locais
  - **docs/** — documentação visual

---

## ⚙️ Tecnologias utilizadas

- HTML5 semântico
- CSS3 com arquitetura SMACSS
- Flexbox + CSS Grid responsivo
- JavaScript Vanilla (sem dependências)
- AOS (Animate On Scroll)
- Google Fonts (Inter)
- WebP com fallback
- CSS Variables para design tokens

---

## 🎨 Features

- Header fixo responsivo
- Menu mobile acessível (ARIA)
- Slider automático de serviços
- Seção de equipe responsiva
- Grid de depoimentos
- CTA focada em conversão
- Integração com Google Maps
- Footer completo com navegação e contatos
- Scroll animations leves

---

## 📱 Responsividade

O projeto utiliza abordagem mobile-first com adaptação para:

- Smartphones
- Tablets
- Notebooks
- Monitores Full HD+

---

## 🚀 Performance

- Lazy loading de imagens
- Uso de WebP
- JavaScript leve sem frameworks
- CSS modularizado
- Estrutura otimizada para carregamento rápido
- Baixo acoplamento entre componentes

---

## 🧠 Decisões técnicas

- Arquitetura **SMACSS** com separação clara (Base/Layout/Components/Utilities)
- JavaScript Vanilla para zero dependências e máxima performance
- CSS Variables para tokens de design (cores, espaçamento, transições)
- Estrutura completamente desacoplada do backend
- Responsividade mobile-first com breakpoints em 768px e 992px
- Header dinâmico com altura ajustável via CSS

---

## 🌐 Deploy

Este projeto foi estruturado para deploy frontend estático utilizando:

- GitHub Pages
- Hospedagem estática CDN
- Deploy simples sem backend integrado

---

## 🔮 Expansões futuras

A arquitetura visual poderá futuramente integrar:

- Backend PHP
- APIs externas
- Sistema de agendamento
- Formulários dinâmicos
- Painel administrativo

Essas funcionalidades serão mantidas em um repositório/backend separado.

---

## 📸 Interface

A interface segue arquitetura visual modular focada em experiência moderna, acessibilidade e conversão.

---

## 📬 Contato

Projeto desenvolvido para fins institucionais e profissionais.

---

---

# 🇺🇸 ENGLISH

## 📌 About the project

This project represents the **static institutional frontend version** of the landing page for **VL Estética & Fisioterapia**.

The application focuses on delivering a modern, responsive, performant, and accessible frontend experience using only frontend technologies.

This version was designed for static deployment through GitHub Pages and works independently from any future backend implementation.

---

## 🎯 Goals

- Build a modern responsive landing page
- Ensure high performance and fast loading
- Create scalable modular CSS architecture
- Implement smooth UX animations
- Improve direct contact conversion
- Maintain reusable frontend architecture

---

## 🧱 Project architecture

The folder structure follows **SMACSS pattern** (Scalable and Modular Architecture for CSS) for clear separation of concerns and scalable maintenance.

> 📌 The full visual structure is documented in the project architecture screenshot.

![Project Architecture](./assets/docs/structure.png)

### General structure

- `/css`
  - **base/** (reset, variables, typography, globals) — Foundation and design tokens
  - **layout/** (header, hero, sections, footer) — Page macro structure
  - **components/** (buttons, cards, slider, testimonials) — Reusable components
  - **utilities/** (containers) — Helpers and utilities

- `/js`
  - **main.js** — global logic, mobile menu, scroll spy
  - **slider.js** — automatic services carousel

- `/assets`
  - **img/** — optimized WebP images
  - **icons/** — SVG icons
  - **fonts/** — local typography
  - **docs/** — visual documentation

---

## ⚙️ Tech stack

- Semantic HTML5
- CSS3 with SMACSS architecture
- Responsive Flexbox + CSS Grid
- Vanilla JavaScript (zero dependencies)
- AOS (Animate On Scroll)
- Google Fonts (Inter)
- WebP with fallback
- CSS Variables for design tokens

---

## 🎨 Features

- Fixed responsive header
- Accessible mobile menu (ARIA)
- Automatic services slider
- Responsive team section
- Testimonials grid
- Conversion-focused CTA
- Google Maps integration
- Full footer navigation
- Lightweight scroll animations

---

## 📱 Responsiveness

Mobile-first approach supporting:

- Smartphones
- Tablets
- Laptops
- Full HD+ displays

---

## 🚀 Performance

- Lazy-loaded images
- WebP image optimization
- Lightweight Vanilla JS
- Modular CSS structure
- Fast-loading architecture
- Low component coupling

---

## 🧠 Technical decisions

- **SMACSS architecture** with clear separation (Base/Layout/Components/Utilities)
- Vanilla JS for zero dependencies and maximum performance
- CSS Variables for design tokens (colors, spacing, transitions)
- Completely backend-independent structure
- Mobile-first responsiveness with breakpoints at 768px and 992px
- Dynamic header with adjustable height via CSS

---

## 🌐 Deployment

This project was designed for static frontend deployment using:

- GitHub Pages
- Static CDN hosting
- Simple deployment without backend integration

---

## 🔮 Future expansions

The visual architecture may later integrate:

- PHP backend
- External APIs
- Appointment scheduling system
- Dynamic forms
- Administrative dashboard

These features will live in a separate backend repository.

---

## 📸 UI Reference

The UI architecture follows a modular system focused on accessibility, performance, and conversion.

---

## 📬 Contact

Project built for professional and institutional purposes.