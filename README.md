# Perceptron_simples_digitos - PYTHON
ALGORITMO PARA CÁLCULO DO PERCEPTRON SIMPLES - PYTHON
INSTRUÇÕES
1- Este algoritmo pode usar a quantidade de entradas que quiser e a quantidade de amostras também que quiser, contanto que mantenha o 1º elemento sendo o Baias e o restante os itens Xn. A mesma estrutura para a amostra de teste.
2- Repartir cada dígito da amostra "2345678" (exemplo usado como divisor de classe) para cada entrada de Xn e colocar no topo.
3- Repetir o mesmo para as amostra seguintes que serão testados de forma aleatória (completa) ou objetiva (mínima):
Completa = Grande quantidade de amostras aleatórias
Mínima = 7 amostras com valores abaixo e 7 amostras com valores acima do alvo, com valores abaixo e acima em cada hipotese dos dígitos Xn.
4- Definir o valor limiar de ativação (normalmente 0).
5- Definir a taxa de aprendizagem (começando com 00.1 e não passando de 2.0).
6- Definir a quantidade de séries/iterações da primeira vez (sugiro começar com 50.0), o resultado dessa amostra de teste anexa só foi satisfatória com uma série de 100000.00.
OBJETIVO
Criar teste para verificar se o valor colocado de entrada está menor (-1) ou maior (+1) do que o divisor de classe "2345678", obtendo ao final do treinamento o neurônio treinado com os pesos Bias + Xn...Xn para criação da fórmula de cálculo.

![image](https://user-images.githubusercontent.com/66335171/188719984-0cce2ce6-8a52-4d18-b3f3-a5c2e96d4ee2.png)


Instalação das bibliotécas pandas e numpy caso não esteja instalado

Importação dos arquivos com amostras para treinamento/alvo e teste/alvo

Função do perceptron simples

Criação de dataframe com multiplicações dos pesos finais x itens para teste

Criação de dataframe consolidador com itens treinados, soma, alvo, resposta e resultado

Exibição de quadro final, pesos finais, erro ao quadrado e quantidade de series/iterações

Exportar vetor de pesos e dataframe final

Referencias:
Implementação do perceptron simples - representação computacional do modelo matemático - Adriano Santos [https://www.youtube.com/watch?v=6hapXAGcgQA]

Redes Neurais: Exemplo do Aprendizado Delta no Perceptron - Fernando dos Santos [https://www.youtube.com/watch?v=TVzysIdNZYw]

Inteligência Artificial na Prática - Profº João Marcos [https://www.youtube.com/watch?v=ZfIb__rg2As&t=122s]
