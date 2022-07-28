# Desafio-Tecnico-Americanas-S.A.
Este repositório contém a minha solução para o Desafio Técnico referente a posição de Cientista de Dados Júnior na Americanas S.A.

Arquivos :

**dataset_cdjr.parquet.gzip** - Dataset utilizado para resolver o desafio.

**Desafio Técnico - Cientista de Dados - Americanas S.A..ipynb** - Contém as seguintes tarefas : Análise Exploratória dos Dados, Preparação dos Dados, Modelagem e Avaliação da Performance do Modelo.

**Entrega do Modelo.ipynb** - Contém a última etapa, apresenta a solução final do desafio e informa como "rodar" a solução construída. Para rodar a solução basta executar a função final_model que possui como único argumento a matriz de features X. Portanto o único cuidado que devemos tomar é escolher a matriz de features sob a qual queremos fazer previsões.

Mais detalhes sobre o arquivo **Desafio Técnico - Cientista de Dados - Americanas S.A..ipynb** :

Este arquivo apresenta todo um estudo sobre o dataset e constrói uma base teórica que nos permite após testarmos vários modelos escolhermos aquele que melhor se adequa aos dados. São feitas considerações sobre a acurácia de diversos modelos tanto no conjunto de treino como em dados não vistos durante o treinamento. Após a escolha do melhor modelo é feita a otimização de alguns hiperparâmetros. Após a otimização do melhor modelo é apresentada a solução final no arquivo **Entrega do Modelo.ipynb** que contém a função final_model. Essa função se utiliza do modelo obtido após o estudo realizado no arquivo **Desafio Técnico - Cientista de Dados - Americanas S.A..ipynb**.

**Análise Exploratória dos Dados** - Leitura do dataset , verificação da dimensão dos dados, análise de valores ausentes, tipos de dados, estatísticas básicas, distribuição da variável target.

**Preparação dos Dados** - Obtenção da matriz de features e do vetor target, Feature Scaling.

**Modelagem** - Treinamento de 10 modelos, verificação da acurácia desses modelos quando realizamos previsões no próprio conjunto de treino.

**Avaliação da Performance do Modelo** - Verificação da acurácia obtida pelos 3 melhores modelos da seção anterior quando avaliados em dados não vistos durante o treinamento, otimização de hiperparâmetros. 
