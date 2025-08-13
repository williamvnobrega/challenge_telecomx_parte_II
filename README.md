# Challenge TelecomX - Parte II

Este repositório contém um notebook Jupyter desenvolvido para a Parte II do Challenge TelecomX, focado na preparação e análise de dados relacionados ao churn de clientes de telecomunicações.

## Descrição

O notebook realiza as seguintes etapas:

1. **Preparação dos Dados**:
   - Importação de bibliotecas essenciais como Pandas, Seaborn e Matplotlib.
   - Carregamento e visualização inicial do dataset `df_limpo.csv`.
   - Limpeza e transformação dos dados, incluindo:
     - Remoção de colunas irrelevantes (como `customerID`).
     - Tratamento de valores ausentes e substituição de categorias.
     - Codificação de variáveis categóricas usando one-hot encoding.

2. **Análise de Correlação e Seleção de Variáveis**:
   - Exploração da distribuição da variável alvo (`Churn_Yes`).
   - Cálculo e visualização da matriz de correlação entre as variáveis para identificar relações significativas.
   - Geração de um heatmap para facilitar a interpretação das correlações.

## Dependências

Para executar o notebook, são necessárias as seguintes bibliotecas Python:
- pandas
- seaborn
- matplotlib
- numpy

## Como Usar

1. Clone o repositório ou faça o download do notebook `challenge_telecomx_parte_II.ipynb`.
2. Certifique-se de que o arquivo `df_limpo.csv` esteja no mesmo diretório ou ajuste o caminho no código.
3. Execute o notebook em um ambiente compatível com Jupyter (como JupyterLab ou Google Colab).


## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

