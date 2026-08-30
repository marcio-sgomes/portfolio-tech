# PORTFOLIO-TECH | MÁRCIO DOS SANTOS GOMES

**Ambiente de Produção:** [INSERIR LINK DA VERCEL AQUI]

## 1. Resumo Executivo
Este repositório documenta o desenvolvimento do portfólio interativo de Márcio dos Santos Gomes. Concebido sob a premissa de um "Meta-Portfólio", a própria construção desta aplicação atua como o produto central. O objetivo primário é tangibilizar competências avançadas em Engenharia de Software e Gestão de Projetos, conectando a base acadêmica em Análise e Desenvolvimento de Sistemas com a especialização em Gestão Ágil de Projetos.

A documentação presente neste repositório reflete estritamente a realidade arquitetural, o código-fonte, as diretrizes de design e a infraestrutura implementada.

---

## 2. Governança e Gestão do Projeto
O ciclo de vida da aplicação é gerenciado através de frameworks ágeis, garantindo previsibilidade, rastreabilidade técnica e alinhamento contínuo com os objetivos do produto.

*   **Board Kanban (GitHub Projects):** [INSERIR LINK AQUI]
    Mapeamento do fluxo de valor, controle de Sprints, gestão de Backlog e rastreamento de tarefas em progresso (WIP) e Code Review.
*   **Product Requirements Document (PRD):** [INSERIR LINK AQUI]
    Documentação detalhada de escopo, requisitos funcionais e não-funcionais, público-alvo e regras de negócio.
*   **Gestão de Mudanças:** 
    Adoção estrita da especificação **Conventional Commits** (`feat`, `fix`, `chore`, `refactor`, `docs`). O histórico de versionamento atua como trilha de auditoria, vinculando diretamente as alterações no código às respectivas *Issues* de governança.

---

## 3. Arquitetura e Engenharia de Software
O sistema foi projetado com foco em manutenibilidade, escalabilidade e baixo acoplamento, seguindo os padrões exigidos para aplicações corporativas.

*   **Clean Architecture:**
    Estruturação do repositório baseada na separação clara de responsabilidades, isolando a lógica de domínio da interface do usuário (UI) e da infraestrutura externa.
*   **Princípios SOLID no Ecossistema React:**
    *   **Single Responsibility Principle (SRP):** Componentes desenhados para executar uma única função estrutural ou de negócio.
    *   **Dependency Inversion Principle (DIP):** Uso de injeção de dependências para chamadas de API e manipulação de estado, evitando acoplamento rígido.
*   **Garantia de Qualidade (Clean Code):**
    Implementação de linters automatizados (ESLint/Prettier) para validação estática do código. Nenhuma alteração fora do padrão arquitetural é permitida na base de código principal.

---

## 4. Infraestrutura e CI/CD
A esteira de integração e entrega contínuas foi desenhada para garantir estabilidade e disponibilidade, bloqueando regressões em produção.

*   **Git Flow & Branching Strategy:**
    Desenvolvimento isolado em ramificações específicas (`feature/`, `fix/`). A ramificação principal (`main`) é protegida e recebe atualizações exclusivamente via Pull Requests revisados.
*   **Pipeline Automatizado (Vercel):**
    Gatilhos de automação configurados para iniciar processos de build e validação a cada Pull Request. O deploy em ambiente de produção ocorre automaticamente após a aprovação das integrações.
*   **Performance e Distribuição:**
    Hospedagem distribuída via Content Delivery Network (CDN) para otimização de latência e tempo de carregamento global.

---

## 5. UI/UX e Design System
A interface do usuário foi previamente especificada e homologada, garantindo consistência visual e eficiência no desenvolvimento front-end.

*   **Especificação Visual (Figma):** [INSERIR LINK AQUI]
*   **Design Tokens:**
    Centralização de variáveis CSS globais baseadas em uma paleta corporativa estrita (Azul Marinho, Cinza Chumbo, Branco e Grafite) e hierarquia tipográfica de alta legibilidade (Inter/Roboto).
*   **Componentização:**
    Desenvolvimento modular categorizado em Átomos (elementos base) e Moléculas (estruturas complexas), promovendo máxima reutilização de código e aderência ao SRP.

---
*Documento de arquitetura atualizado iterativamente a cada Sprint concluída.*