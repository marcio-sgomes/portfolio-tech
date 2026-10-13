# ROADMAP E ÉPICOS DE DESENVOLVIMENTO
**Projeto:** Portfolio-Tech
**Metodologia:** Ágil (Kanban)

Este documento mapeia o ciclo de vida de desenvolvimento do projeto, dividido em Épicos funcionais e arquiteturais. A execução das tarefas ocorre de forma iterativa, com rastreamento via GitHub Projects.

> Os Épicos 1 e 2 foram executados neste repositório; os Épicos 3 a 5 no repositório de código [portfolio-marcio-gomes](https://github.com/marcio-sgomes/portfolio-marcio-gomes) (referências `PMG#n` apontam para as issues de lá).

---

## ÉPICO 1: Concepção e Governança ✅
**Objetivo:** Estruturar a fundação do projeto, documentação e processos de gestão.
- [x] Definição de escopo e arquitetura de informação (PRD).
- [x] Configuração da estrutura de repositório e diretórios (`docs/`).
- [x] Setup do Board Kanban e definição de padronização de commits (Conventional Commits).

## ÉPICO 2: Design System e UI/UX
**Objetivo:** Especificação visual e prototipação de alta fidelidade.
- [x] Definição de Design Tokens (Paleta de cores "Tech Executive" e Tipografia Inter/Roboto). (#4)
- [x] Prototipação de componentes Átomos e Moléculas no Figma. (botões #5 e #6, card de projeto #8)
- [ ] Desenho das telas base (Hero, Trajetória, Cases e Bastidores). — *parcial: Hero desenhada (#7)*

## ÉPICO 3: Infraestrutura e CI/CD
**Objetivo:** Automação de pipeline e ambiente de produção.
- [ ] Configuração do repositório para proteção da branch `main`. — *pendente ([PMG#27](https://github.com/marcio-sgomes/portfolio-marcio-gomes/issues/27))*
- [x] Integração com Vercel para deploy contínuo. ([PMG#10](https://github.com/marcio-sgomes/portfolio-marcio-gomes/issues/10))
- [ ] Configuração de validação estática de código (bloqueio de merges com erro). — *parcial: CI com lint, testes e build roda em cada PR ([PMG#9](https://github.com/marcio-sgomes/portfolio-marcio-gomes/issues/9)), mas ainda não bloqueia o merge*

## ÉPICO 4: Arquitetura Frontend e Clean Code
**Objetivo:** Setup do ecossistema React com foco em Clean Architecture.
- [x] Inicialização do projeto React (Vite). ([PMG#1](https://github.com/marcio-sgomes/portfolio-marcio-gomes/issues/1))
- [x] Estruturação de pastas (Domain, Application, UI). — *implementada como `domain`, `data` e `presentation` ([PMG#2](https://github.com/marcio-sgomes/portfolio-marcio-gomes/issues/2))*
- [ ] Configuração de Linters (ESLint, Prettier) e regras de padronização. — *parcial: ESLint configurado; Prettier pendente ([PMG#27](https://github.com/marcio-sgomes/portfolio-marcio-gomes/issues/27))*

## ÉPICO 5: Desenvolvimento de Componentes e Interface
**Objetivo:** Tradução do Figma para código React seguindo princípios SOLID.
- [x] Implementação de tokens CSS/Styled Components. — *feita com variáveis CSS + CSS Modules ([PMG#6](https://github.com/marcio-sgomes/portfolio-marcio-gomes/issues/6))*
- [x] Criação dos componentes estruturais orientados ao Princípio da Responsabilidade Única (SRP). (Header, ProjectCard, páginas Início e Sobre)
- [ ] Integração do conteúdo da narrativa profissional e casos de estudo (Bela Brisa). — *pendente ([PMG#24](https://github.com/marcio-sgomes/portfolio-marcio-gomes/issues/24))*

---
*Progresso atualizado em outubro de 2026.*
