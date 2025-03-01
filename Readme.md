# Sistema Metroviário e Ferroviário de São Paulo

## Introdução
Os meios de transporte são fundamentais para o desenvolvimento econômico das cidades. Dentre os modais terrestres, destacam-se o **sistema ferroviário** e o **sistema metroviário**.

Este projeto analisa e representa graficamente a estrutura das **linhas de trem e metrô do Estado de São Paulo**, utilizando bibliotecas como **Pandas, Geopandas, NetworkX e Matplotlib**.

## Contexto Histórico
- **Sistema Ferroviário**: Inaugurado em 16 de fevereiro de 1867, com a estrada de ferro **São Paulo Railway (SPR)**, que conectava Jundiaí a Santos. Atualmente, é administrado pela **CPTM** desde 1992.
- **Sistema Metroviário**: Criado oficialmente em 24 de abril de 1968, pelo então prefeito **Brigadeiro Faria Lima**. A primeira linha foi inaugurada entre **Jabaquara e Saúde**.

## Objetivo do Projeto
O projeto tem como objetivo:
1. **Carregar e estruturar os dados** de estações de trem e metrô de São Paulo.
2. **Construir um grafo** representando a interligação entre as estações.
3. **Visualizar os mapas** do sistema ferroviário e metroviário de São Paulo.

## Tecnologias Utilizadas
- **Python**: Linguagem principal do projeto.
- **Pandas**: Manipulação e análise de dados tabulares.
- **Geopandas**: Manipulação de dados geoespaciais.
- **NetworkX**: Cria e analisa grafos do sistema de transporte.
- **Matplotlib**: Geração de visualizações gráficas.

## Estrutura do Código
O código realiza as seguintes etapas:
1. **Importa as bibliotecas necessárias**.
2. **Carrega os dados** dos arquivos CSV e Shapefile.
3. **Verifica a existência dos arquivos** no sistema.
4. **Cria um grafo** contendo as estações como nós e as conexões como arestas.
5. **Define cores** para diferenciar cada linha de trem e metrô.
6. **Plota os mapas** com e sem legenda.

## Como Executar
1. Clone o repositório ou copie o código para um ambiente Python.
2. Instale as dependências necessárias (caso ainda não tenha):
   ```bash
   pip install pandas geopandas networkx matplotlib
   ```
3. Certifique-se de que os arquivos de dados estão no local correto.
4. Execute o código Python para visualizar os mapas do sistema de transporte.

## Resultados Esperados
- Um **mapa interativo** que mostra todas as estações do Metrô e da CPTM em São Paulo.
- Um **grafo colorido** representando as conexões entre as estações.
- Identificação de integrações entre os diferentes modais de transporte.

## Contribuição
Caso queira contribuir com o projeto, faça um **fork** do repositório, implemente melhorias e envie um **pull request**.

## Licença
Este projeto é de uso livre e aberto para estudos e melhorias.

