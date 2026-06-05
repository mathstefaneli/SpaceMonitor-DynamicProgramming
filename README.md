# SpaceMonitor - Dynamic Programming

## Aluno

Matheus Gomes Stefaneli

RM 562277

---

## Definição do Problema

O projeto SpaceMonitor tem como objetivo auxiliar no monitoramento ambiental utilizando dados obtidos por satélites.

Diversas regiões são monitoradas constantemente para identificar eventos ambientais como queimadas, enchentes, secas e tempestades.

Quando um evento é detectado, é necessário identificar rapidamente as áreas conectadas para facilitar a tomada de decisão e o planejamento das equipes de resposta.

Para resolver esse problema foi utilizada uma estrutura de grafos contendo 35 áreas monitoradas e conceitos de Programação Dinâmica para evitar cálculos repetidos.

---

## Estrutura Utilizada

Foi utilizado um grafo para representar as áreas monitoradas.

Cada área corresponde a um vértice do grafo.

As conexões representam possíveis rotas entre as regiões monitoradas.

O sistema possui 35 áreas monitoradas, atendendo ao requisito de possuir mais de 30 informações.

---

## Lógica da Solução

Inicialmente são criadas 35 áreas monitoradas.

As áreas são conectadas através de um grafo.

O algoritmo calcula o menor custo para percorrer as áreas monitoradas.

Para evitar cálculos repetidos, é utilizada a técnica de memoização.

A memoização armazena resultados previamente calculados e reutiliza esses valores quando necessário.

Essa técnica é um dos conceitos fundamentais da Programação Dinâmica.

---

## Funções Utilizadas

### menor_caminho()

Responsável por calcular o menor custo entre as áreas monitoradas.

### mostrar_rotas()

Responsável por exibir os resultados obtidos pelo algoritmo.

As funções foram implementadas utilizando a palavra-chave `def`.

---

## Tecnologias Utilizadas

* Python
* Google Colab
* GitHub

---

## Conclusão

A solução demonstra a utilização de grafos e Programação Dinâmica em um cenário relacionado ao monitoramento ambiental por satélites.

A utilização da memoização reduz o processamento necessário e torna o sistema mais eficiente para consultas repetidas.
