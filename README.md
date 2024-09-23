Análise Exploratória de Dados com Python
Este projeto realiza uma Análise Exploratória de Dados (EDA) utilizando dados de preços de fechamento e volumes de negociação de produtos da Nvidia. Através de visualizações estatísticas e resumos descritivos, o objetivo é identificar padrões, tendências e relações nos dados que possam auxiliar em tomadas de decisões informadas.

Funcionalidades
Download de Dados via Google Drive: O projeto baixa automaticamente o arquivo CSV armazenado no Google Drive para processamento local.
Análise Exploratória de Dados (EDA):
Histograma dos Preços de Fechamento: Visualiza a distribuição dos preços de fechamento.
Gráfico de Dispersão: Mostra a relação entre as datas e os preços de fechamento.
Gráfico de Barras: Demonstra o volume de negociação ao longo do tempo.
Bibliotecas Utilizadas
pandas: Manipulação e análise de dados tabulares.
matplotlib: Criação de gráficos.
seaborn: Visualizações estatísticas sofisticadas.
requests: Para fazer requisições HTTP e baixar arquivos.
StringIO: Para manipular o conteúdo de arquivos em memória.
Como Executar o Projeto
Clone o repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Instale as dependências necessárias:

bash
Copiar código
pip install pandas matplotlib seaborn requests
Execute o script:

bash
Copiar código
python eda_script.py
Exemplos de Visualizações
Histograma dos Preços de Fechamento:

O histograma mostra a distribuição dos preços de fechamento, ajudando a identificar intervalos de preço mais comuns.
Gráfico de Dispersão (Data vs Preço de Fechamento):

O gráfico de dispersão permite visualizar a evolução dos preços de fechamento ao longo do tempo.
Gráfico de Barras (Volume de Negociação por Data):

O gráfico de barras destaca o volume de negociação por data, facilitando a identificação dos dias de maior ou menor volume de transações.
Relatório
O resumo estatístico dos dados revela medidas descritivas como média, mediana, desvio padrão, entre outros.
O histograma mostra a distribuição dos preços de fechamento, permitindo identificar padrões nos intervalos de preços.
O gráfico de dispersão ajuda a identificar tendências e flutuações no preço ao longo do tempo.
O gráfico de barras demonstra a variação do volume de negociação por data, fornecendo insights sobre os dias com maior ou menor atividade de mercado.
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request para melhorias.
