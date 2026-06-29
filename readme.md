# Gerador de Currículo ATS

Projeto web criado para analisar a compatibilidade entre um currículo e uma descrição de vaga, simulando uma análise ATS.

A aplicação permite que o usuário insira informações do currículo, cole a descrição de uma vaga e receba uma análise com score, palavras-chave encontradas, palavras-chave ausentes e recomendações de melhoria.

---

## Objetivo

O objetivo do projeto é ajudar candidatos a avaliarem se o currículo está alinhado com uma vaga específica.

Muitos processos seletivos utilizam sistemas ATS para filtrar currículos com base em palavras-chave, experiências, habilidades e requisitos da vaga. Este projeto simula uma análise inicial para orientar o candidato a melhorar a organização do currículo e aumentar a aderência com a vaga desejada.

A proposta é melhorar a apresentação das informações sem inventar experiências, cargos, empresas ou certificações.

---

## Funcionalidades

* Inserção de dados do candidato
* Campo para descrição da vaga
* Análise de compatibilidade ATS
* Score de compatibilidade de 0 a 100
* Extração de palavras-chave
* Identificação de palavras-chave encontradas
* Identificação de palavras-chave ausentes
* Identificação de gaps entre currículo e vaga
* Recomendações automáticas de melhoria
* Geração de resumo profissional otimizado
* Prévia do currículo
* Opção para copiar o resultado
* Interface simples e responsiva
* Estrutura organizada para portfólio

---

## Fluxo do Sistema

```text
Usuário acessa a aplicação
        ↓
Preenche os dados do currículo
        ↓
Cola a descrição da vaga
        ↓
Clica em analisar
        ↓
O sistema compara currículo e vaga
        ↓
O sistema identifica palavras-chave
        ↓
O sistema calcula o score ATS
        ↓
O resultado é exibido na tela
        ↓
O usuário recebe recomendações de melhoria
```

---

## Tecnologias Utilizadas

* HTML
* CSS
* JavaScript
* Lovable
* GitHub

---

## Estrutura do Projeto

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
```

---

## Documentação

A pasta `docs/` contém documentos de apoio para explicar o funcionamento e a evolução do projeto:

* `arquitetura.md`: descreve a estrutura técnica do projeto.
* `fluxo-do-sistema.md`: apresenta o fluxo de uso da aplicação.
* `prompts-usados.md`: registra os prompts utilizados no desenvolvimento.
* `melhorias-futuras.md`: lista possíveis evoluções do projeto.

---

## Screenshots

### Tela Inicial

![Tela Inicial](screenshots/tela%20inicial.png)

### Análise de Currículo

![Análise de Currículo](screenshots/Analise%20de%20curriculo.png)

### Currículo do Candidato

![Currículo do Candidato](screenshots/Curriculo%20candidato.png)

---

## Como Executar o Projeto

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/gerador-curriculo-ats.git
```

Acesse a pasta do projeto:

```bash
cd gerador-curriculo-ats
```

Instale as dependências:

```bash
npm install
```

Execute o projeto localmente:

```bash
npm run dev
```

Depois, acesse no navegador o endereço exibido no terminal.

---

## Diferencial do Projeto

Este projeto resolve um problema real enfrentado por candidatos que precisam adaptar seus currículos para vagas publicadas em plataformas como Gupy, LinkedIn e sistemas internos de recrutamento.

Além disso, o projeto demonstra conhecimentos em:

* Desenvolvimento web
* Organização de projeto
* Experiência do usuário
* Lógica de análise textual
* Documentação técnica
* Uso de IA no processo de criação
* Construção de solução aplicada a carreira e empregabilidade

---

## Regras da Análise

O sistema deve seguir uma regra importante:

> Não inventar experiências, cargos, empresas, certificações ou habilidades.

A proposta é apenas reorganizar, destacar e melhorar as informações reais informadas pelo candidato.

---

## Melhorias Futuras

* Integração com IA generativa
* Exportação em PDF
* Exportação em DOCX
* Upload de currículo em PDF ou DOCX
* Histórico de análises
* Login de usuários
* Banco de dados
* Dashboard de evolução do score
* Comparação do currículo com múltiplas vagas
* Geração de carta de apresentação
* Versão em inglês

---

## Status do Projeto

Projeto em desenvolvimento e organizado para portfólio.

A versão atual contempla a estrutura inicial da aplicação, documentação, telas principais e proposta de análise ATS.

---

## Autor

Desenvolvido por **Ronaldo Augusto Sabino**.

Projeto criado com foco em carreira, tecnologia, inteligência artificial e melhoria de currículos para processos seletivos.
