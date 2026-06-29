
---

# Arquitetura do Projeto — Gerador de Currículo ATS

## 1. Visão Geral

O Gerador de Currículo ATS é uma aplicação web criada para analisar a compatibilidade entre um currículo e uma descrição de vaga.

O sistema recebe informações profissionais do candidato, compara com os requisitos da vaga e apresenta uma análise com score ATS, palavras-chave encontradas, palavras-chave ausentes e recomendações de melhoria.

## 2. Objetivo da Arquitetura

A arquitetura foi pensada para ser simples, funcional e fácil de apresentar em portfólio.

Os principais objetivos são:

- Manter o projeto leve e fácil de executar.
- Concentrar a aplicação em um arquivo principal.
- Facilitar publicação no GitHub Pages.
- Permitir evolução futura com IA, banco de dados ou exportação de arquivos.
- Documentar a solução de forma clara.

## 3. Estrutura de Pastas

```bash
gerador-curriculo-ats/
│
├── docs/
│   ├── arquitetura.md
│   ├── fluxo-do-sistema.md
│   ├── melhorias-futuras.md
│   └── prompts-usados.md
│
├── screenshots/
│   ├── Analise de curriculo.png
│   ├── Curriculo candidato.png
│   └── tela inicial.png
│
├── .env.example
├── .gitignore
├── index.html
├── package.json
└── readme.md
