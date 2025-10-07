📊 Comparação de Algoritmos de Ordenação
Este projeto é um estudo prático de algoritmos de ordenação, comparando o desempenho de quatro abordagens distintas: Selection Sort, Merge Sort, Radix Sort e Timsort. O objetivo é analisar o impacto da complexidade assintótica (notação Big O) no tempo de execução, uso de memória e outras métricas, em diferentes cenários de entrada de dados.

🚀 Como Usar o Projeto
Você pode rodar todo o experimento no Google Colab sem a necessidade de instalar nada localmente.

Opção 1: Abrir no Google Colab (Recomendado)
Clique no botão abaixo para abrir o notebook diretamente no Google Colab. Todo o ambiente de execução e as bibliotecas já estarão prontas.

Substitua [Seu_Usuario], [Seu_Repositorio] e nome_do_seu_notebook.ipynb pelos dados do seu projeto.

Opção 2: Executar Localmente
Se preferir rodar o notebook em sua máquina local, siga os passos abaixo.

Pré-requisitos
Python 3.8+

Bibliotecas: Instale as bibliotecas necessárias usando o pip.

Bash

pip install pandas matplotlib
Execução
Clone o repositório para sua máquina local:

Bash

git clone https://github.com/[Seu_Usuario]/[Seu_Repositorio].git
cd [Seu_Repositorio]
Abra o notebook nome_do_seu_notebook.ipynb em seu ambiente de desenvolvimento preferido (Jupyter Notebook, VS Code, etc.).

Execute as células uma a uma, seguindo a ordem para gerar os dados, rodar os experimentos e visualizar os resultados.

🧪 Metodologia do Experimento
O experimento compara os algoritmos em quatro métricas principais, em cenários controlados:

Tempo de Execução: Medido em segundos.

Uso de Memória: Pico de memória consumida (em KB).

Comparações: Número de comparações lógicas entre elementos.

Movimentos/Trocas: Número de rearranjos de elementos na memória.

Os testes são realizados com listas de diferentes tamanhos (n) e em quatro cenários de entrada:

Aleatório: Para simular o caso médio.

Ordenado: Para testar o melhor caso.

Em Ordem Inversa: Para testar o pior caso.

Aleatório com Grande Variação: Para desafiar o Radix Sort.

📈 Análise dos Algoritmos
Os resultados do notebook geram gráficos e tabelas que confirmam as características de cada algoritmo:

Selection Sort (O(n 
2
 )): Ineficiente para grandes entradas, mas com o número mínimo de trocas. Ideal para fins didáticos.

Merge Sort (O(nlogn)): Desempenho robusto e previsível em todos os cenários, mas com custo de memória adicional.

Radix Sort (O(d⋅n)): O mais rápido para a ordenação de números inteiros, pois não realiza comparações, mas com alto consumo de memória.

Timsort (O(n) a O(nlogn)): O mais eficiente na prática, servindo como padrão em linguagens como Python e Java, pois se adapta à estrutura dos dados de entrada.

📚 Referências
Kaggle Dataset: https://www.kaggle.com/docs/datasets

GeeksforGeeks: https://pt.wikipedia.org/wiki/Algoritmo_de_ordena%C3%A7%C3%A3o

Documentação Python: https://deinfo.uepg.br/~alunoso/2019/AEP/TIMSORT/REA-TimSort.htm

