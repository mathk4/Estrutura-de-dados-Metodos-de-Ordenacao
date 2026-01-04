# Estrutura de dados Métodos de Ordenação

Feito por Matheus Rodrigues Silva e Larissa R. Gabriel

Este projeto foi desenvolvido como trabalho final da disciplina de Estrutura de Dados durante o 3º semestre do curso de Engenharia de Computação.
O objetivo principal é analisar o desempenho de diferentes algoritmos de ordenação aplicados a um conjunto de dados real 
------------

## Projeto

O código carrega dados de um arquivo CSV contendo informações da NASA sobre asteroides e outros objetos espaciais.
A aplicação realiza a ordenação desses objetos com base no seu ID, comparando o tempo de execução de quatro algoritmos clássicos em diferentes cenários de estresse.

Algoritmos Implementados

• Bubble Sort;
• Selection Sort;
• Merge Sort;
• Quick Sort.

------ 

## Metodologia

Para garantir uma análise robusta, o programa executa e mostra o tempo de execução dos algoritmos sob as seguintes condições:

• Variação de Tamanho: Testes com arrays de 50.000 até 350.000 elementos (incrementos de 50k).

Cenários de Dados:

• Aleatório: Dados lidos diretamente do CSV;
• Ordenado: Teste de performance com o vetor já organizado;
• Reverso: Teste de performance com o vetor inversamente ordenado.

Apos a aplicação dos algorítimos, os resultados foram transcritos para tabelas para melhor visualização.
-----
## Importante ao Executar

• Ter o java instalado
• Fazer o Dowload do Dataset
• Alterar o caminho para o Dataset no arquivo main 
