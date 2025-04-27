# Análise de Assortatividade em Grafos de Ingredientes da Culinária Brasileira

## Autor:  
### • Maurício Matheus Araújo Silva Galvão - Engenharia de Computação  

Link para o vídeo: https://drive.google.com/drive/u/0/folders/1lUTCXclKlW-XkqAFRhldlotX-Tt8DdHS

O Objetivo desta tarefa é construir um grafo de co-ocorrência de ingredientes de receitas da culinária brasileira. Os ingredientes foram classificados por tipo, além de ter sido analisada a assortatividade do grafo criado.  

Foram utilizadas as seguintes bibliotecas para análise: `networkx`, `pandas`, `numpy`, `nxviz`,  `matplotlib.pyplot`, `itertools` e `IPython Display`.  

Ao ser analisada a assortatividade dos diferentes tipos de ingredientes das 50 receitas da culinária brasileira, pôde-se observar uma assortatividade negativa, representando heterofilia. Foi visualizado no grafo gerado que ingredientes não tendem a ser usados com ingredientes do mesmo tipo, mas sim com tipos diferentes, o que é algo coerente no ponto de vista culinário.


### Grafo gerado: 

![image](https://github.com/user-attachments/assets/539ebf3f-2235-4089-a036-69a94364000a)  

Para uma análise mais precisa e eficiente, os nós foram agrupados com base em seus tipos/cores, para que a assortatividade negativa ficasse mais evidente.
