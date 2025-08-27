## 📊 Análise de Regressão: Impacto de Modalidades de Exercício na Queima Calórica

Este projeto realiza uma análise estatística completa para investigar como diferentes tipos de treino (Cardio, HIIT, Strength e Yoga) e variáveis biométricas influenciam a queima de calorias, com foco especial nas diferenças entre gêneros.

### 🔍 Técnicas Utilizadas:
- **Regressão Linear Múltipla** com variáveis padronizadas
- **Seleção de variáveis** via método Backward com critérios BIC e Cp
- **Regressão Polinomial** com termos quadráticos
- **Diagnóstico completo de modelos** (VIF, Cook's Distance, DFFITS, DFBETAS)
- **Análise exploratória** com visualizações ggplot2 e matriz de correlação
- **Teste de pressupostos** com pacote gvlma

### 📈 Principais Descobertas:
- Duração do treino é o fator mais relevante para queima calórica
- Gênero apresenta influência significativa mesmo controlando outras variáveis
- Tipo de exercício tem impacto marginal quando consideradas outras variáveis
- Modelos polinomiais mostraram-se superiores aos lineares
