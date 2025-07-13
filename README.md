# Analise_Diabetes_Regressao
Aplicação da análise de Regressão para determinar os factores que influenciam a Diabetes
O Objetivo principal:
- Analisar e modelar a relação entre variáveis clínicas e a progressão da diabetes em pacientes;
- identificar factores importantes e prever o valor da variável target (Variavel dependente).

# 1. Análise Exploratória de Dados (EDA)


-Entender a estrutura e distribuição das variáveis
1.Algumas variáveis, como bmi, bp e s5, mostram distribuições relativamente simétricas.
2.Outras, como s1 e s6, têm distribuição mais dispersa.

-Identificar variáveis mais correlacionadas com a progressão da diabetes

-Ver padrões, outliers entre outras caracteristicas.


# 2. Modelagem com Regressão Linear


- Estimar como cada variável influencia a progressão da diabetes

- Criar um modelo capaz de prever a diabestes com base nas características dos pacientes

- Interpretar os coeficientes.
  
# 3. Avaliação do modelo

- Verificar se o modelo é adequado (via R² e erro quadrático médio)

- Analisar os resíduos para validar os pressupostos do modelo

- Avaliar se a regressão linear é suficiente ou se há necessidade de modelos mais avançados

# Conclusão:
Com esta análise, conclui-se que:
- bmi e s5  tem uma relação linear forte com target.
- bp mostra uma relação mais fraca, mas visível.
- Variáveis como sex e s6 têm pouca influência.
- bmi, bp e s5 têm correlação positiva moderada com target.
-s3 tem correlação negativa fraca com target.

Avaliação do modelo:
-R² = 0.45: o modelo explica aproximadamente 45% da variância da variável dependente: isto, indica uma capacidade baixa de explicação da variabilidade da progressão da doença
- Erro médio quadrático (MSE) foi relativamente baixo
- Desempenho razoável para dados médicos com ruído.

NB: Para se melhorar o   modelo, pode se recorrer a mmodelos mais avancados, como a regressão linear explicou apenas cerca de 45% da variância da variável alvo, en aconselhavel aplicar modelos mais avançados de machine learning, que conseguem capturar relações não lineares nos dados.

 
