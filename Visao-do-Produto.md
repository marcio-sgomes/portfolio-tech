# DOCUMENTO DE VISÃO DO PRODUTO (PRD)
**Projeto:** Portfolio-Tech
**Proprietário:** Márcio dos Santos Gomes
**Data de Atualização:** Agosto de 2026

## 1. Introdução e Propósito
O projeto "Portfolio-Tech" é uma aplicação web interativa concebida para atuar como um meta-portfólio. Diferente de um currículo estático ou uma galeria de imagens, o propósito deste software é comprovar proficiência técnica através da sua própria estrutura de desenvolvimento. 

A aplicação materializa a capacidade do desenvolvedor de integrar a base teórica de Análise e Desenvolvimento de Sistemas e a especialização em Gestão de Projetos Ágeis com a prática de engenharia de front-end, servindo como ferramenta de validação para recrutadores e clientes.

## 2. Público-Alvo
*   **Recrutadores Técnicos e Tech Leads:** Profissionais em busca de desenvolvedores Front-end (React/JavaScript) que demonstrem conhecimento em arquitetura limpa e testes, indo além da criação de interfaces.
*   **Gestores de TI / Engineering Managers:** Líderes que valorizam profissionais com visão de produto, domínio de metodologias ágeis e práticas de CI/CD.
*   **Clientes de Consultoria B2B:** Organizações que necessitam de estruturação de processos, organização ágil ou desenvolvimento de soluções sistêmicas.

## 3. Escopo Funcional (Requisitos de Negócio)
A aplicação deve prover as seguintes funcionalidades ao usuário final:
*   **Apresentação Executiva (Hero):** Identificação imediata do profissional, proposta de valor e chamadas para ação (Download de CV e Contato).
*   **Exposição de Trajetória e Formação:** Seção dedicada à fundamentação acadêmica, destacando a graduação na Estácio e a pós-graduação na Faveni.
*   **Módulo de Cases Práticos:** Exibição de projetos reais, com destaque para a consultoria de processos estruturada para a Associação Comunitária Bela Brisa, focando em identificação de problemas e implementação de metodologias.
*   **Laboratório Técnico:** Área para demonstração de experimentações e domínio do ecossistema React, JavaScript, HTML e CSS.
*   **Documentação Integrada (O Meta-Portfólio):** Acesso direto à infraestrutura do projeto, evidenciando o quadro Kanban, repositório de código e pipeline de CI/CD.

## 4. Escopo Não-Funcional (Requisitos Técnicos)
As premissas arquiteturais que governam o desenvolvimento da aplicação:
*   **Desempenho e Disponibilidade:** Single Page Application (SPA) desenvolvida em React, com otimização de *bundle size* e hospedada em CDN (Vercel) para alta disponibilidade.
*   **Arquitetura e Qualidade:** Adoção de Clean Architecture na separação de diretórios. O código deve respeitar os princípios SOLID e passar por validação estática via ESLint e Prettier antes de qualquer *merge*.
*   **Design e Usabilidade:** Interface responsiva (Mobile First) governada por um Design System proprietário com tipografia de alta legibilidade (Inter/Roboto) e paleta de cores corporativa.
*   **Governança:** Versionamento semântico (Conventional Commits) e gerenciamento de tarefas via Kanban (GitHub Projects).

## 5. Arquitetura da Informação (Sitemap)
A navegação será estruturada de forma linear (One-Page Scroll) com ancoragem de seções, contendo:
1.  **Header:** Navegação global fixa.
2.  **Seção 1 (Hero):** Apresentação, pitch executivo e botões principais.
3.  **Seção 2 (Fundamentos):** Formação acadêmica e matriz de competências (Hard/Soft Skills).
4.  **Seção 3 (Cases & Consultoria):** Histórico de atuação técnica e gerencial.
5.  **Seção 4 (Arquitetura & Engenharia):** Explicação da governança do próprio portfólio.
6.  **Footer:** Links institucionais (LinkedIn, GitHub) e e-mail de contato.