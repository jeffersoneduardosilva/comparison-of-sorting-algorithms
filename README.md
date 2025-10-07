📊 Comparação de Algoritmos de Ordenação
========================================

Este projeto é um estudo prático de algoritmos de ordenação, comparando o desempenho de quatro abordagens distintas: **Selection Sort**, **Merge Sort**, **Radix Sort** e **Timsort**. O objetivo é analisar o impacto da complexidade assintótica (notação Big O) no tempo de execução, uso de memória e outras métricas, em diferentes cenários de entrada de dados.

🚀 Como Usar o Projeto
----------------------

Você pode rodar todo o experimento no Google Colab ou em sua máquina local usando o VS Code.

### Opção 1: Abrir no Google Colab (Recomendado)

Clique no botão abaixo para abrir o notebook diretamente no Google Colab. Todo o ambiente de execução e as bibliotecas já estarão prontas.

_Substitua \[Seu\_Usuario\], \[Seu\_Repositorio\] e nome\_do\_seu\_notebook.ipynb pelos dados do seu projeto._

### Opção 2: Executar Localmente (VS Code)

Se preferir rodar o notebook em sua máquina local com o VS Code, siga os passos abaixo.

#### Pré-requisitos

*   **Python 3.8+** instalado.
    
*   **VS Code** com a extensão **Jupyter** instalada.
    
*   Bashpip install pandas matplotlib
    

#### Execução

1.  Bashgit clone https://github.com/\[Seu\_Usuario\]/\[Seu\_Repositorio\].gitcd \[Seu\_Repositorio\]
    
2.  Abra o VS Code e, no menu, selecione File > Open Folder... para abrir a pasta do projeto.
    
3.  Abra o arquivo nome\_do\_seu\_notebook.ipynb no VS Code. A extensão do Jupyter será ativada automaticamente.
    
4.  No canto superior direito do notebook, selecione o interpretador Python que você instalou para o projeto.
    
5.  Execute as células uma a uma, clicando no ícone de "Play" ao lado de cada uma, para gerar os dados, rodar os experimentos e visualizar os resultados.
    

🧪 Metodologia do Experimento
-----------------------------

O experimento compara os algoritmos em quatro métricas principais, em cenários controlados:

1.  **Tempo de Execução:** Medido em segundos.
    
2.  **Uso de Memória:** Pico de memória consumida (em KB).
    
3.  **Comparações:** Número de comparações lógicas entre elementos.
    
4.  **Movimentos/Trocas:** Número de rearranjos de elementos na memória.
    

Os testes são realizados com listas de diferentes tamanhos (n) e em quatro cenários de entrada:

*   **Aleatório:** Para simular o caso médio.
    
*   **Ordenado:** Para testar o melhor caso.
    
*   **Em Ordem Inversa:** Para testar o pior caso.
    
*   **Aleatório com Grande Variação:** Para desafiar o Radix Sort.
    

📈 Análise dos Algoritmos
-------------------------

Os resultados do notebook geram gráficos e tabelas que confirmam as características de cada algoritmo:

*   **Selection Sort (O(n2)):** Ineficiente para grandes entradas, mas com o número mínimo de trocas. Ideal para fins didáticos.
    
*   **Merge Sort (O(nlogn)):** Desempenho robusto e previsível em todos os cenários, mas com custo de memória adicional.
    
*   **Radix Sort (O(d⋅n)):** O mais rápido para a ordenação de números inteiros, pois não realiza comparações, mas com alto consumo de memória.
    
*   **Timsort (O(n) a O(nlogn)):** O mais eficiente na prática, servindo como padrão em linguagens como Python e Java, pois se adapta à estrutura dos dados de entrada.
    

📚 Referências
--------------

*   **Kaggle Dataset**: [https://www.kaggle.com/docs/datasets](https://www.kaggle.com/docs/datasets)
    
*   **GeeksforGeeks**: [https://pt.wikipedia.org/wiki/Algoritmo\_de\_ordenação](https://pt.wikipedia.org/wiki/Algoritmo_de_ordenação)
    
*   **Documentação Python**: [https://deinfo.uepg.br/~alunoso/2019/AEP/TIMSORT/REA-TimSort.htm](https://deinfo.uepg.br/~alunoso/2019/AEP/TIMSORT/REA-TimSort.htm)
