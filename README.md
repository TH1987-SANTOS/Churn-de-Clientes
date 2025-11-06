# Detecção de Churn de Clientes

Projeto de análise e modelagem para **detecção de churn (cancelamento) de clientes**.
Este repositório contém um notebook com EDA, pré-processamento e um modelo de classificação treinado para identificar clientes em risco de cancelamento.

## Conteúdo
- `churn_clientes.ipynb` — Notebook com: carregamento dos dados, EDA, pré-processamento, modelagem e avaliação.
- `churn_dataset.csv` — Dataset (não incluído no repositório por segurança) — coloque o arquivo na mesma pasta do notebook para reproduzir o fluxo.
- `README.md` — Este arquivo.
- `requirements.txt` — Lista de dependências para reproduzir o ambiente.

## Resumo dos principais achados (do notebook)
- **Média de chamadas ao suporte (todos os clientes):** 5.40 chamadas.
- **Média de chamadas — não cancelaram:** 4.50 chamadas.
- **Média de chamadas — cancelaram:** 6.40 chamadas.  
  > Clientes que cancelaram fizeram, em média, ~42% mais chamadas ao suporte do que os que permaneceram.
- **Duração média de contrato (meses):** ~5.31 meses — clientes que cancelam tendem a ter contratos ligeiramente mais curtos.

> Observação: no notebook atual foi treinado **um único modelo de classificação** (sem aplicação de balanceamento SMOTE). Se quiser comparar modelos ou aplicar balanceamento, há células sugeridas no notebook (comentadas) para execução.



