# Méliuz — Case Técnico Product Manager Pleno

Este repositório contém minha resolução para o case técnico da vaga de **Product Manager Pleno** da Méliuz.

O objetivo do case foi analisar um experimento relacionado ao **In-App Browser** da plataforma, identificar os principais aprendizados do teste e propor a próxima evolução do produto com visão orientada a negócio, experimentação e experiência do usuário.

A entrega foi estruturada em:
- uma análise completa do experimento A/B/C;
- uma proposta de evolução do produto em formato de PRD;
- um notebook analítico contendo toda a exploração e validação dos dados.

---

# Estrutura do Repositório

```text
meliuz-pm-case/
│
├── entrega-1/
│   └── Entrega 1.pdf
│
├── entrega-2/
│   └── Entrega 2.pdf
│
└── notebook/
    └── Case_Técnico_—_PM_Pleno_(Ecommerce_App).ipynb
```

---

# Entrega 1 — Análise do Experimento

A primeira entrega teve como foco reconstruir o experimento A/B/C e responder às principais perguntas de produto relacionadas ao uso do In-App Browser.

## Principais tópicos abordados

- Entendimento do contexto do experimento
- Trade-offs entre In-App Browser e navegador externo
- Reconstrução das variantes A/B/C
- Limpeza e validação dos dados
- Construção da tabela analítica
- Análise de conversão e receita
- Análise comportamental por tipo de saída
- Validação estatística dos resultados
- Recomendação de rollout
- Estratégia escalável para experimentação em produto

## Principais conclusões

- O **In-App Browser** continua sendo a principal jornada do produto;
- A variante **Header** aumentou saídas externas, mas degradou conversão e receita;
- A variante **Config** apresentou melhor equilíbrio entre flexibilidade e preservação da jornada;
- O principal ponto de fricção identificado parece estar relacionado ao fluxo de autenticação/login.

### Arquivo

```text
entrega-1/Entrega 1.pdf
```

---

# Entrega 2 — Próxima Melhoria

A segunda entrega propõe uma evolução do produto baseada diretamente nos aprendizados da análise anterior.

## Melhoria proposta

### Fallback Inteligente de Login

A proposta consiste em oferecer abertura contextual para navegador externo apenas quando forem detectados sinais de fricção relacionados a autenticação dentro do In-App Browser.

O objetivo é:
- reduzir abandono;
- preservar tracking e retenção;
- evitar saídas impulsivas;
- manter a jornada principal saudável;
- melhorar a experiência em cenários específicos de fricção.

## O documento contém

- Diagnóstico do problema
- Hipótese de produto
- Contexto de negócio
- PRD completo da solução
- Escopo do MVP
- Critérios de aceite
- Instrumentação e tracking
- Estratégia experimental
- Métricas de sucesso e guardrails
- Plano de rollout
- Breakdown técnico para engenharia

### Arquivo

```text
entrega-2/Entrega 2.pdf
```

---

# Notebook Analítico

O notebook contém toda a exploração técnica utilizada durante a análise.

## Conteúdo do notebook

- Carregamento e entendimento dos datasets
- Limpeza e validação dos dados
- Joins e construção da tabela analítica
- Parsing dos parâmetros de tracking
- Criação das variantes experimentais
- Criação do `exit_type`
- Métricas de conversão e receita
- Visualizações
- Testes estatísticos
- Geração de insights comportamentais e de produto

### Arquivo

```text
notebook/Case_Técnico_—_PM_Pleno_(Ecommerce_App).ipynb
```

---

# Ferramentas Utilizadas

- Python
- Pandas
- Google Colab
- Matplotlib
- Statsmodels

---

# Abordagem Utilizada

Ao longo da resolução, busquei estruturar a análise não apenas sob uma perspectiva analítica, mas também considerando:
- impacto de negócio;
- trade-offs de produto;
- experiência do usuário;
- governança de experimentação;
- escalabilidade operacional;
- comunicação entre Produto, Engenharia e Analytics.

A proposta foi tratar o case de forma próxima ao contexto real de operação de um time de produto orientado por experimentação.

---

# Observação

Conforme solicitado no enunciado do case, este repositório foi mantido privado.
