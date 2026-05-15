# Análise de Desempenho no SAT — Escolas Públicas de NYC

Análise exploratória do desempenho de escolas públicas de Nova York no exame SAT, identificando padrões por escola e por região (borough).

## Objetivo

Responder perguntas sobre desempenho acadêmico a partir de dados reais de escolas públicas de Nova York, utilizando filtragem, agregação e análise estatística com pandas.

## Perguntas respondidas

- Quais escolas atingem pelo menos 80% da pontuação máxima em matemática?
- Quais são as 10 escolas com maior pontuação total no SAT?
- Qual borough apresenta maior variabilidade de desempenho entre suas escolas?

## Tecnologias utilizadas

- Python 3
- pandas
- estatística descritiva (média, desvio padrão)

## Principais etapas

1. Leitura e exploração inicial do dataset
2. Filtragem por critério de performance (≥ 80% do máximo em matemática)
3. Criação de coluna derivada (total SAT = matemática + leitura + escrita)
4. Agrupamento por borough com cálculo de média e desvio padrão
5. Identificação do borough com maior variabilidade de resultados

## Arquivos

| Arquivo | Descrição |
|---|---|
| `notebook.ipynb` | Análise exploratória completa |
## Dataset

Dados públicos de desempenho no SAT de escolas públicas de Nova York (NYC).
