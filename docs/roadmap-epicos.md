# ROADMAP E ÉPICOS DE DESENVOLVIMENTO
**Projeto:** Portfolio-Tech
**Metodologia:** Ágil (Kanban)

Este documento mapeia o ciclo de vida de desenvolvimento do projeto, dividido em Épicos funcionais e arquiteturais. A execução das tarefas ocorre de forma iterativa, com rastreamento via GitHub Projects.

---

## ÉPICO 1: Concepção e Governança (Fase Atual)
**Objetivo:** Estruturar a fundação do projeto, documentação e processos de gestão.
- [x] Definição de escopo e arquitetura de informação (PRD).
- [x] Configuração da estrutura de repositório e diretórios (`docs/`).
- [x] Setup do Board Kanban e definição de padronização de commits (Conventional Commits).

## ÉPICO 2: Design System e UI/UX
**Objetivo:** Especificação visual e prototipação de alta fidelidade.
- [ ] Definição de Design Tokens (Paleta de cores "Tech Executive" e Tipografia Inter/Roboto).
- [ ] Prototipação de componentes Átomos e Moléculas no Figma.
- [ ] Desenho das telas base (Hero, Trajetória, Cases e Bastidores).

## ÉPICO 3: Infraestrutura e CI/CD
**Objetivo:** Automação de pipeline e ambiente de produção.
- [ ] Configuração do repositório para proteção da branch `main`.
- [ ] Integração com Vercel para deploy contínuo.
- [ ] Configuração de validação estática de código (bloqueio de merges com erro).

## ÉPICO 4: Arquitetura Frontend e Clean Code
**Objetivo:** Setup do ecossistema React com foco em Clean Architecture.
- [ ] Inicialização do projeto React (Vite).
- [ ] Estruturação de pastas (Domain, Application, UI).
- [ ] Configuração de Linters (ESLint, Prettier) e regras de padronização.

## ÉPICO 5: Desenvolvimento de Componentes e Interface
**Objetivo:** Tradução do Figma para código React seguindo princípios SOLID.
- [ ] Implementação de tokens CSS/Styled Components.
- [ ] Criação dos componentes estruturais orientados ao Princípio da Responsabilidade Única (SRP).
- [ ] Integração do conteúdo da narrativa profissional e casos de estudo (Bela Brisa).