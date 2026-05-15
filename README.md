# 🎸 SoloDash - Vitrine Digital e Gestão Inteligente

> **SoloDash** é uma Single Page Application (SPA) de alta performance projetada para profissionalizar a carreira de artistas independentes. O projeto une música, tecnologia e inteligência artificial para resolver dores reais de gestão e prospecção.

---

## 📝 Descrição do Projeto
O SoloDash funciona como uma vitrine inteligente para o músico Joelson Ramos. Criada como uma SPA nativa, a plataforma automatiza propostas via **SoloAI**, protege negociações com um **Chat Seguro (filtros Regex)** e centraliza a gestão de agenda e repertório. É a ponte tecnológica entre o talento artístico e a segurança comercial.

## ✨ Funcionalidades Core (MVP)
- 🤖 **SoloAI:** Assistente generativo que redige pitches e propostas comerciais automaticamente.
- 🛡️ **Chat Anti-Calote:** Sistema de mensagens com motor Regex que bloqueia a troca de dados sensíveis fora do ambiente seguro.
- 🎵 **Player Persistente:** Áudio contínuo que não interrompe durante a navegação entre abas do dashboard.
- 📅 **Agenda Interativa:** Sistema de bloqueio de datas e gestão de disponibilidade em tempo real.
- 📱 **Mobile-First & 60 FPS:** Interface ultra-responsiva com animações processadas via GPU.

## 🛠️ Stack Tecnológica
- **Frontend:** HTML5, CSS3 (Design Tokens), Vanilla JavaScript (ES6+).
- **Arquitetura:** SPA (Single Page Application) com padrão modular inspirado em MVC.
- **AI:** Integração com APIs de processamento de linguagem natural.
- **Segurança:** Validação via Expressões Regulares (Regex) e sanitização de DOM.

## 🚀 DevOps & Deployment
- **Versionamento:** GitHub (Gitflow).
- **CI/CD:** GitHub Actions integrado com **Vercel** para Continuous Deployment.
- **Monitorização:** Sentry (planeado) para observabilidade de erros no client-side.
- **Gestão:** Metodologia Ágil (Scrum) com backlog gerido no Jira/Trello.

## 📁 Estrutura de Pastas
```text
SoloDash/
├── assets/          # Imagens, Ícones e Logos
├── css/             # Estilização (variáveis e temas)
├── js/              # Lógica, Motores Regex e SoloAI
├── index.html       # Entry point (SPA)
└── README.md        # Documentação principal
