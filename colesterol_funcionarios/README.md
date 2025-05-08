# Análise de Colesterol dos Colaboradores

Este projeto tem como objetivo analisar os níveis de colesterol de 220 colaboradores de uma empresa, como parte de um programa de saúde corporativa. A pergunta principal é: o colesterol médio dos funcionários está dentro dos limites considerados aceitáveis (até 190 mg/dL)?

## Etapas da análise

- Leitura dos dados em formato Excel
- Visualização da distribuição dos valores com histograma e curva de densidade
- Verificação de normalidade usando o Teste de Shapiro-Wilk
- Teste de hipótese (teste t unilateral) para verificar se a média é maior que 190 mg/dL
- Interpretação dos resultados com base no valor-p

## Conclusão

A média observada foi de 192,26 mg/dL e o valor-p unilateral foi 0,043.  
Como o valor-p é menor que 0,05, rejeitamos a hipótese nula.  
Portanto, há evidência estatística de que o colesterol médio dos colaboradores está acima do limite aceitável.

## Ferramentas utilizadas

- Python (bibliotecas: pandas, scipy, matplotlib, seaborn)
- Google Colab

## Organização dos arquivos

- `notebook.ipynb`: análise completa no Colab
- `imagens/`: gráficos gerados durante a análise
- `dados/`: base de dados utilizada (se permitido compartilhar)
