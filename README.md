# Análise de Risco e Retorno de Setores do Ibovespa

Análise comparativa do desempenho de 5 setores da B3 nos últimos 12 meses (jul/2025 – jul/2026), avaliando retorno, risco e oportunidades de diversificação.

## Setores analisados

| Setor | Ativo | Ticker |
|-------|-------|--------|
| Financeiro | Itaú Unibanco | ITUB4 |
| Energia | Petrobras | PETR4 |
| Consumo | Ambev | ABEV3 |
| Commodities | Suzano | SUZB3 |
| Utilities | Cemig | CMIG4 |

## Principais resultados

| Setor | Retorno | Volatilidade | Sharpe | Drawdown Máx |
|-------|---------|-------------|--------|-------------|
| Financeiro | +40.22% | 23.24% | 1.03 | -21.20% |
| Energia | +37.37% | 25.16% | 0.89 | -22.16% |
| Consumo | +24.93% | 26.06% | 0.50 | -14.40% |
| Utilities | +16.13% | 22.82% | 0.21 | -21.47% |
| Commodities | -15.01% | 26.79% | -0.96 | -32.72% |

## Etapas do projeto

1. **Coleta de dados** — cotações históricas via Yahoo Finance (yfinance)
2. **Validação e limpeza** — verificação de dados faltantes, preços absurdos e buracos no calendário
3. **Cálculo de retornos** — retornos diários percentuais a partir do preço de fechamento ajustado
4. **Análise exploratória** — retorno acumulado e gráfico de risco x retorno
5. **Indicadores** — Sharpe Ratio, volatilidade anualizada, matriz de correlação e drawdown máximo
6. **Conclusões** — insights acionáveis sobre eficiência setorial e diversificação

## Ferramentas

- Python 3.14
- pandas
- matplotlib
- yfinance
- Jupyter Notebook

## Como rodar

```bash
pip install notebook yfinance pandas matplotlib
jupyter notebook
```

Abra o arquivo `analise-setorial-ibovespa.ipynb` e execute as células em ordem.

## Autor

Moisés Maia — Julho 2026
