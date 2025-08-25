# Análise de Rotatividade de Funcionários - Framework DDPP

## 📋 Visão Geral do Projeto

Este projeto fornece uma análise abrangente da rotatividade de funcionários usando o framework DDPP (Descritiva → Diagnóstica → Preditiva → Prescritiva). A análise foi realizada em um dataset de 9.540 funcionários para identificar fatores-chave que influenciam a rotatividade e desenvolver estratégias acionáveis de retenção.

## 🎯 Objetivo de Negócio

Analisar dados de rotatividade de funcionários para:
- Identificar principais fatores que influenciam a saída dos funcionários
- Desenvolver um modelo preditivo para identificar funcionários em risco
- Propor plano de ação baseado em dados para reter talentos
- Reduzir custos associados à rotatividade de funcionários

## 🚨 SITUAÇÃO CRÍTICA IDENTIFICADA

Nossa análise de 9.540 registros de funcionários revela uma **SITUAÇÃO DE ROTATIVIDADE SIGNIFICATIVA**:
- **Taxa anual de rotatividade de 29,2%** (média da indústria: 15-20%)
- **Custo anual estimado entre $129M-$162M** (análise conservadora)
- **Aproximadamente 2.352 funcionários em alto risco** de saída

Esta situação demanda atenção executiva imediata e intervenção estratégica baseada em análise de cenários realistas.

## 📊 Principais Descobertas

### Estatísticas Críticas
- **Taxa Geral de Rotatividade**: 29,2% (NÍVEL ELEVADO)
- **Funcionários em Alto Risco**: ~2.352 (aproximadamente 25% da força de trabalho)
- **Custo Anual da Rotatividade**: $129M-$162M (estimativa conservadora)
- **Economia Anual Potencial**: $13M-$58M (dependendo do cenário de implementação)

### Principais Fatores de Risco
1. **Baixa Satisfação**: Principal driver da rotatividade
2. **Tempo na Empresa**: Funcionários no início da carreira apresentam maior risco
3. **Avaliações de Performance**: Correlação com decisões de saída
4. **Departamento**: Gestão de Produtos e Vendas mostram maior risco
5. **Nível Salarial**: Faixa salarial baixa mostra 42% de taxa de risco

### Perfil dos Departamentos de Alto Risco
- IT: 30,9% de taxa de risco
- Logistics: 30,8% de taxa de risco
- Retail: 30,6% de taxa de risco
- Marketing: 30,3% de taxa de risco
- Support: 28,8% de taxa de risco

## 💰 ANÁLISE FINANCEIRA REALISTA

### Premissas Conservadoras Adotadas
- **Custo médio por saída**: $46,25K (análise conservadora)
  - Recrutamento e contratação: $33,75K (75% do salário)
  - Treinamento e integração: $8K
  - Perda de produtividade (2 meses): $7,5K
- **Custo anual atual**: $129M (2.784 saídas × $46,25K)

### 📊 ANÁLISE DE SENSIBILIDADE - MÚLTIPLOS CENÁRIOS

#### Cenário Conservador (Recomendado)
- **Redução de rotatividade**: 10%
- **Investimento**: $400K
- **Economia anual**: $12,9M
- **ROI**: 8,4%
- **Payback**: 37,2 meses
- **Risco**: BAIXO

#### Cenário Moderado
- **Redução de rotatividade**: 20%
- **Investimento**: $350K
- **Economia anual**: $25,8M
- **ROI**: 26,6%
- **Payback**: 16,2 meses
- **Risco**: MÉDIO

#### Cenário Otimista
- **Redução de rotatividade**: 30%
- **Investimento**: $300K
- **Economia anual**: $38,7M
- **ROI**: 44,7%
- **Payback**: 9,3 meses
- **Risco**: ALTO

### 🎯 ANÁLISE DE RISCO AVANÇADA

Considerando fatores de incerteza (taxa de sucesso, variação de custos, retenção pós-programa):
- **Pior caso**: ROI de -30,9% (necessita revisão de estratégia)
- **Cenário provável**: ROI de 18,6% (atrativo para investimento)
- **Melhor caso**: ROI de 68,0% (excelente retorno)

### 💡 RECOMENDAÇÃO ESTRATÉGICA
**PROSSEGUIR COM CAUTELA** - Implementar com cenário conservador-moderado, priorizando:
1. Piloto com departamentos de maior risco
2. Monitoramento mensal de KPIs
3. Ajustes baseados em resultados reais

## 📁 Estrutura do Projeto

```
Turnover_Qoder/
├── 📊 employee_churn_data.csv          # Dataset original (9.540 funcionários)
├── 📓 analise_rotatividade_Qoder.ipynb       # 🏆 ARQUIVO PRINCIPAL - Análise completa DDPP
├── 📁 outputs/                         # Visualizações geradas
│   ├── 01_taxa_rotatividade_geral.png
│   ├── 02_descriptive_analysis.png
│   ├── 03_correlation_matrix.png
│   ├── 04_feature_importance.png
│   ├── 04_matriz_correlacao.png
│   ├── 05_analise_roi_sensibilidade.png
│   └── test_churn_distribution.png
├── 🤖 modelos/                        # Modelos de machine learning
│   ├── modelo_rotatividade.pkl         # Modelo Random Forest treinado
│   ├── scaler.pkl                      # Scaler para preprocessamento
│   ├── label_encoder_dept.pkl          # Encoder para departamentos
│   └── label_encoder_salary.pkl        # Encoder para salários
└── 📋 README.md                        # Este arquivo
```

## 🔬 Metodologia (Framework DDPP)

### Fase 1: Análise Descritiva
- **Objetivo**: O que está acontecendo com a rotatividade?
- **Saídas**: Estatísticas gerais, análise de distribuição
- **Insight Principal**: Taxa de rotatividade de 29,2% indica problema organizacional significativo

### Fase 2: Análise Diagnóstica
- **Objetivo**: Por que os funcionários estão saindo?
- **Saídas**: Análise de correlação, distribuições comparativas
- **Insight Principal**: Satisfação, tenure e avaliação são os principais preditores da rotatividade

### Fase 3: Análise Preditiva
- **Objetivo**: Quem vai sair em seguida?
- **Saídas**: Modelos de machine learning, pontuação de risco
- **Melhor Modelo**: Random Forest com métricas realistas de performance
- **Resultado**: 2.352 funcionários identificados como alto risco (>70% probabilidade)

### Fase 4: Análise Prescritiva
- **Objetivo**: Que ações devemos tomar?
- **Saídas**: Plano de ação, análise de ROI, framework de monitoramento
- **Meta**: 30% de redução na taxa de rotatividade
- **ROI Esperado**: 8,4% a 44,7% dependendo do cenário de implementação

## 📈 Variáveis do Dataset

| Variável | Descrição | Tipo |
|----------|-----------|------|
| satisfaction | Nível de satisfação do funcionário (0-1) | Numérica |
| review | Score da última avaliação de performance (0-1) | Numérica |
| projects | Número de projetos ativos | Numérica |
| avg_hrs_month | Horas médias mensais trabalhadas | Numérica |
| tenure | Anos na empresa | Numérica |
| work_accident | Teve acidente de trabalho (0/1) | Binária |
| promoted | Promovido nos últimos 24 meses (0/1) | Binária |
| department | Departamento do funcionário | Categórica |
| salary | Nível salarial (low/medium/high) | Categórica |
| left | Funcionário saiu da empresa (0/1) | Variável Target |

## 🚀 Como Usar

### Requisitos Técnicos
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy joblib
```

### Execução
```bash
# Abrir Jupyter Notebook
jupyter notebook

# Navegar para o arquivo principal
analise_rotatividade_Qoder.ipynb

# Executar todas as células
Cell → Run All
```

### Saídas Geradas
- **Visualizações**: Automaticamente salvas na pasta `outputs/`
- **Modelos**: Modelo treinado salvo como `outputs/modelo_rotatividade.pkl`
- **Relatórios**: Conclusões integradas no próprio notebook

## 🎯 RECOMENDAÇÕES ESTRATÉGICAS

### AÇÕES IMEDIATAS (Próximos 30 Dias)
**Investimento**: $50K-$100K (baseado no cenário escolhido)

1. **Auditoria Emergencial de Satisfação**
   - Implementar pesquisa de satisfação em toda a empresa
   - Identificar riscos imediatos de saída (>80% probabilidade)
   - Conduzir entrevistas de saída com funcionários recentes

2. **Intervenção para Funcionários de Alto Risco**
   - Reuniões pessoais com 2.352 funcionários de alto risco
   - Ofertas imediatas de retenção para top 1% performers em risco
   - Redistribuição de carga de trabalho para funcionários sobrecarregados (>250h/mês)

3. **Revisão Emergencial de Compensação**
   - Ajuste salarial para high-performers na faixa "baixa"
   - Implementação de estrutura de bônus para retenção
   - Benchmarking com taxas de mercado

**Impacto Esperado**: 15% de redução imediata de risco

### INICIATIVAS DE CURTO PRAZO (30-90 Dias)
**Investimento**: $150K-$200K (baseado no cenário escolhido)

1. **Programas Específicos por Departamento**
   - Reformulação da liderança de Gestão de Produtos
   - Reestruturação da equipe de Vendas e redesign de incentivos
   - Otimização de processos de Contabilidade

2. **Lançamento de Desenvolvimento de Carreira**
   - Planos de desenvolvimento individual para todos os funcionários
   - Estabelecimento de programa de mentoria
   - Comunicação de critérios claros de promoção

3. **Melhoria do Equilíbrio Vida-Trabalho**
   - Arranjos de trabalho flexíveis
   - Monitoramento e controles de hora extra
   - Programas de saúde mental e bem-estar

**Impacto Esperado**: 10% adicional de redução de risco

### TRANSFORMAÇÃO DE LONGO PRAZO (90 Dias - 1 Ano)
**Investimento**: $100K-$200K (baseado no cenário escolhido)

1. **Transformação Cultural**
   - Treinamento de liderança em engajamento de funcionários
   - Iniciativas de melhoria de comunicação
   - Programas de reconhecimento e apreciação

2. **Sistema de Monitoramento Preditivo**
   - Dashboard de avaliação de risco em tempo real
   - Alertas automatizados de alerta precoce
   - Reuniões mensais de revisão de risco

3. **Otimização do Design Organizacional**
   - Reestruturação de departamentos baseada na análise de risco
   - Implementação de algoritmo de alocação de projetos
   - Programa de planejamento de sucessão

**Impacto Esperado**: Atingir meta de redução entre 10%-30% (conforme cenário implementado)

## 🤖 Modelo Preditivo

### Performance do Modelo
- **Algoritmo**: Random Forest Classifier
- **Acurácia**: 60,6%
- **Precisão**: 62,1%
- **Recall**: 45,6%
- **F1-Score**: 52,4%
- **AUC**: 62,5%

### Principais Features Preditivas
1. Nível de satisfação
2. Anos na empresa (tenure)
3. Score da avaliação de performance
4. Número de projetos
5. Horas trabalhadas por mês

### Uso do Modelo
```python
import joblib
model = joblib.load('outputs/modelo_rotatividade.pkl')
scaler = joblib.load('outputs/scaler.pkl')

# Prever probabilidade de rotatividade para dados de novo funcionário
probability = model.predict_proba(scaled_features)[:, 1]
risk_level = "Alto" if probability > 0.7 else "Médio" if probability > 0.4 else "Baixo"
```

## 📊 Principais Visualizações

1. **Distribuição Geral de Rotatividade**: Gráfico de pizza e barras mostrando 29,2% de rotatividade
2. **Análise Departamental**: Taxas de rotatividade por departamento e nível salarial
3. **Matriz de Correlação**: Relacionamentos entre todas as variáveis numéricas
4. **Importância das Features**: Quais fatores mais predizem rotatividade
5. **🆕 Análise de Sensibilidade ROI**: Comparação visual de cenários e avaliação de riscos

## 📈 MÉTRICAS DE SUCESSO E MONITORAMENTO

### KPIs Primários
- **Taxa geral de rotatividade**: Meta 20,4%-26,3% (de 29,2%)
- **Contagem de funcionários de alto risco**: Meta <1.500 (de 2.352)
- **Taxas de risco departamental**: Todos os departamentos <25%
- **Scores de satisfação**: Meta >0,65 média (melhoria gradual)
- **ROI do programa**: Mínimo 8% (cenário conservador)

### Relatórios Mensais
- Taxa de rotatividade por departamento
- Contagem de funcionários de alto risco e intervenções
- Economia de custos alcançada vs. meta
- Acompanhamento de ROI do programa

### Alertas Automatizados
- Score de risco do funcionário >80%: Alerta imediato ao gerente
- Rotatividade departamental >35%: Escalação para RH
- Declínio de satisfação >15%: Trigger de investigação

## 🛠️ Requisitos Técnicos

### Dependências
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy joblib
```

### Execução
```bash
# Executar análise completa
jupyter notebook analise_rotatividade_Qoder.ipynb
```

## ⚠️ FATORES DE RISCO E MITIGAÇÃO

### Riscos de Implementação
1. **Resistência da Liderança**: Mitigar através de demonstração clara de ROI
2. **Restrições Orçamentárias**: Mostrar que economia imediata de custos compensa investimento
3. **Ceticismo dos Funcionários**: Comunicação transparente sobre mudanças genuínas
4. **Prioridades Concorrentes**: Posicionar como iniciativa crítica para o negócio

### Dependências de Sucesso
- Comprometimento da liderança executiva
- Treinamento e buy-in dos gerentes
- Execução consistente do programa
- Monitoramento regular do progresso

## 🎉 RESULTADOS ESPERADOS

### Resultados Financeiros (Cenário Moderado)
- **Ano 1**: $25,8M em economia de custos
- **Anos 2-3**: $51,6M adicionais em economia
- **Impacto total de 3 anos**: $77M+ em criação de valor
- **ROI sustentável**: 26,6% no cenário moderado

### Benefícios Organizacionais
- Melhoria do moral e engajamento dos funcionários
- Reputação aprimorada da empresa como empregador de escolha
- Aumento da produtividade de funcionários experientes retidos
- Redução da carga de recrutamento e treinamento
- Melhor atendimento ao cliente de equipes estáveis

### Vantagem Competitiva
- Taxas de retenção líderes da indústria
- Atração de top talentos
- Ganhos de eficiência operacional
- Cultura organizacional mais forte


### Conteúdo do Notebook Principal

O arquivo `analise_rotatividade.ipynb` contém **TODA** a análise em um único documento estruturado:

#### 1️⃣ **Fase Descritiva**
- ✅ Importação e configuração de bibliotecas
- ✅ Carregamento e exploração inicial dos dados
- ✅ Análise de dados faltantes
- ✅ Taxa geral de rotatividade (29.2%)
- ✅ Distribuições por categoria e variáveis numéricas
- ✅ Visualizações salvas em outputs/

#### 2️⃣ **Fase Diagnóstica**
- ✅ Tratamento de dados faltantes
- ✅ Matriz de correlação
- ✅ Análise comparativa por status de saída
- ✅ Segmentação por satisfação, horas e salário
- ✅ Testes estatísticos (qui-quadrado, t-test)

#### 3️⃣ **Fase Preditiva**
- ✅ Preparação dos dados para modelagem
- ✅ Encoding de variáveis categóricas
- ✅ Treinamento de modelos (Random Forest, Logistic Regression)
- ✅ Avaliação de performance
- ✅ Identificação de funcionários em risco (2.352 em alto risco)
- ✅ Salvamento do modelo treinado

#### 4️⃣ **Fase Prescritiva**
- ✅ Análise de impacto financeiro com múltiplos cenários
- ✅ Análise de sensibilidade e avaliação de riscos
- ✅ Cálculo de ROI realista (8,4% a 44,7%)
- ✅ Simulação Monte Carlo para validação
- ✅ Plano de ação estruturado (imediato, médio e longo prazo)
- ✅ Recomendações específicas por departamento
- ✅ Estratégia de monitoramento contínuo com medidas de mitigação

## 📞 Suporte e Contato

Para questões sobre esta análise ou suporte de implementação, entre em contato com a equipe de ciência de dados.

---

**Nota**: Esta análise fornece insights baseados em dados para tomada de decisão estratégica. A implementação deve ser adaptada ao contexto organizacional específico e requisitos legais.

**Status**: ✅ **PROJETO COMPLETO E PRONTO PARA IMPLEMENTAÇÃO**  
**Arquivo Principal**: `analise_rotatividade_Qoder.ipynb`  
**Framework**: DDPP (Descritiva → Diagnóstica → Preditiva → Prescritiva)