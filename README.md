# Booking - Previsão de Cancelamentos
## Introdução
```
Projeto destinado a análises da base de dados de reservas do Booking, 
para gerar insights e modelagem preditiva.
```
## Objetivo
```
Criação de um modelo preditivo para realizar a predição do cancelamento
das reservas da plataforma.
```
## Metodologia
```
Para esse projeto foi utilizado o modelo de Floresta Aleatória usando
o seguinte passo a passo para a modelagem:
1. Data Preparing: Preparação dos dados
2. Feature Engineering: Criação de novas features
3. Análise Exploratória: Para identificar padrões de comportamento 
                         e hipóteses para o problema
4. Recursive Feature Elimination: Uso da técnica de RFE para encontrar
                                as features que apresentam maior importância
                                para a modelagem do problema
5. Modelagem: Treino e teste do modelo de Floresta Aleatória
```

## Estrutura do repositório

```
.
├── data
│   ├── intermediate   <-- dados intermediários gerados para análise.
│   ├── processed      <-- dados finais com as predições.
│   └── raw            <-- dados brutos utilizados no projeto.
├── models             <-- modelos treinados e serializados.
├── notebooks          <-- Jupyter notebooks criados para o projeto.
├── README.md          <-- documentação base do projeto.
└── requirements.txt   <-- dependências do projeto.
```
