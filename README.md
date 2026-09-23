# Questão 2 - Padrão Decorator (Padaria)

Este repositório contém a solução da Questão 2 da atividade de Padrões de Projetos Orientados a Objetos. O objetivo da atividade foi refatorar um sistema de pedidos de uma padaria, aplicando o **Padrão Decorator** para permitir a combinação dinâmica de diferentes enfeites de bolos (camadas, granulado e frases) sem alterar as classes base e sem criar uma explosão de subclasses.

## Documentação do Uso de IA

A Inteligência Artificial (Gemini) foi utilizada como uma ferramenta de tutoria guiada, auxiliando no passo a passo da implementação arquitetural e na construção de um histórico de versionamento semântico.

### Prompts Utilizados

Durante a resolução desta questão, os seguintes prompts foram enviados à IA:

1. **Solicitação do Passo a Passo (Questão 2):** *"segunda questão, monte um passo a passo de como eu resolvo isso: [Texto do Enunciado]"*
2. **Fornecimento do Código Base:** *"aqui estão os arquivos [Códigos de Cake.java, ChocolateCake.java, Main.java, Order.java e VanillaCake.java]"*
3. **Geração da Documentação:** *"cria o README.md pra mim, que ajusto o que ficar diferente"*

---

### Intervenções e Análise Crítica

**Por que a abordagem puramente automática da IA / geradores de código poderia falhar?**
N/A

## Estrutura de Commits
A evolução da refatoração pode ser lida no git log deste repositório. Foi adotado o padrão Conventional Commits (utilizando prefixos como feat, refactor e docs) para garantir que o histórico de versionamento conte de forma clara e linear a história da aplicação do Padrão Strategy.