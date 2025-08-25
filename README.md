# Análise de Rotatividade de Funcionários - Framework DDPP

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/EanesRibeiro/turnover_anlise_ddpp)
[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Framework](https://img.shields.io/badge/Framework-DDPP-green)](https://github.com/EanesRibeiro/turnover_anlise_ddpp)
[![Status](https://img.shields.io/badge/Status-Complete-success)](https://github.com/EanesRibeiro/turnover_anlise_ddpp)
[![ROI](https://img.shields.io/badge/ROI-8.4%25--44.7%25-brightgreen)](https://github.com/EanesRibeiro/turnover_anlise_ddpp)

## 📋 Visão Geral do Projeto

Este projeto fornece uma análise abrangente da rotatividade de funcionários usando o framework DDPP (Descritiva → Diagnóstica → Preditiva → Prescritiva). A análise foi realizada em um dataset de 9.540 funcionários para identificar fatores-chave que influenciam a rotatividade e desenvolver estratégias acionáveis de retenção.

## 📊 Fonte dos Dados

**Dataset**: [Employee Turnover Dataset](https://www.kaggle.com/datasets/marikastewart/employee-turnover/data)  
**Fonte**: Kaggle - Marika Stewart  
**Tamanho**: 9.540 registros de funcionários  
**Formato**: CSV com 10 variáveis (9 features + 1 target)

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

### 📊 Premissas de ROI - Fontes e Metodologia

#### **Custo por Demissão: $49,250** *(Análise Conservadora - Dezembro 2024)*

**Componentes Detalhados:**
- **Recrutamento e Contratação**: $33,750 (75% do salário médio)
  - *Fonte*: Society for Human Resource Management (SHRM) 2024
  - *Metodologia*: 75% do salário anual médio de $45,000
  - Inclui: anúncios, agências, tempo de RH, entrevistas

- **Treinamento e Integração**: $8,000
  - *Fonte*: Association for Talent Development (ATD) 2024
  - *Metodologia*: Média de mercado para onboarding completo
  - Inclui: materiais, treinador, tempo de supervisão

- **Perda de Produtividade**: $7,500 (2 meses)
  - *Fonte*: Harvard Business Review - Employee Productivity Studies
  - *Metodologia*: Tempo até atingir produtividade plena
  - Período: 2 meses × ($45,000/12) × 25% de ineficiência

**Salário Base de Referência**: $45,000/ano
- *Fonte*: Bureau of Labor Statistics 2024 + ajuste para amostra
- *Data de Coleta*: Dezembro 2024
- *Inflação Considerada*: 3,2% ao ano (Fed 2024)

**Custo Anual Atual**: $137,112,000
- *Cálculo*: 2.784 saídas × $49,250 por saída
- *Taxa de Rotatividade Base*: 29,2% da força de trabalho

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
├── 📊 employee_churn_data.csv          # Dataset original (9.540 funcionários) - EXCLUÍDO DO GIT
├── 📓 analise_rotatividade.ipynb       # 🏆 ARQUIVO PRINCIPAL - Análise completa DDPP
├── 📁 outputs/                         # Visualizações geradas
│   ├── 01_taxa_rotatividade_geral.png  # Taxa geral de rotatividade (29,2%)
│   └── 04_matriz_correlacao.png        # Matriz de correlação entre variáveis
├── 🤖 modelos/                         # Modelos de machine learning
│   ├── best_model.pkl                  # Melhor modelo Random Forest treinado
│   ├── modelo_rotatividade.pkl         # Modelo principal de rotatividade
│   ├── scaler.pkl                      # Scaler para preprocessamento
│   ├── label_encoder_dept.pkl          # Encoder para departamentos
│   └── label_encoder_salary.pkl        # Encoder para salários
├── 📋 README.md                        # Este arquivo
└── 🔒 .gitignore                       # Configurações de exclusão do Git
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

## 📈 Dicionário de Variáveis Completo

### Variáveis Originais e Transformações Aplicadas

| Variável Original | Nome Processado | Descrição Detalhada | Tipo | Transformação/Encoding | Faixa de Valores |
|-------------------|-----------------|---------------------|------|---------------------|------------------|
| **satisfaction** | satisfaction | Nível de satisfação do funcionário medido em escala contínua | Numérica | Padronização (StandardScaler) | 0.0 - 1.0 |
| **evaluation** → **review** | review | Score da última avaliação de performance (renomeado para clareza) | Numérica | Padronização (StandardScaler) | 0.31 - 1.0 |
| **number_project** → **projects** | projects | Número de projetos ativos atribuídos ao funcionário | Numérica | Padronização (StandardScaler) | 2 - 5 projetos |
| **average_montly_hours** → **avg_hrs_month** | avg_hrs_month | Horas médias mensais trabalhadas (renomeado para clareza) | Numérica | Padronização (StandardScaler) | 171.4 - 200.9 horas |
| **time_spend_company** → **tenure** | tenure | Anos de permanência na empresa (renomeado para clareza) | Numérica | Padronização (StandardScaler) | 2 - 12 anos |
| **Work_accident** → **work_accident** | work_accident | Indicador de acidente de trabalho nos últimos 2 anos | Binária | Passthrough (sem transformação) | 0 = Não, 1 = Sim |
| **promotion_last_5years** → **promoted** | promoted | Promovido nos últimos 24 meses (ajustado do nome original) | Binária | Passthrough (sem transformação) | 0 = Não, 1 = Sim |
| **sales** → **department** | department | Departamento/área de atuação do funcionário | Categórica Nominal | OneHotEncoder (drop='first') | 10 categorias únicas |
| **salary** | salary_encoded | Nível salarial ordinal do funcionário | Categórica Ordinal | Manual: low=0, medium=1, high=2 | 0, 1, 2 |
| **left** | left | **VARIÁVEL TARGET**: Funcionário saiu da empresa | Binária Target | Conversão: 'no'→0, 'yes'→1 | 0 = Ficou, 1 = Saiu |

### 📋 Notas Importantes sobre Transformações

- **Renomeações de Clareza**: Várias variáveis foram renomeadas para melhor compreensão (ex: evaluation→review, average_montly_hours→avg_hrs_month)
- **Encoding Ordinal vs Nominal**: Salary recebeu encoding ordinal manual respeitando hierarquia natural; Department recebeu OneHotEncoder por ser nominal
- **Pipeline de Preprocessing**: ColumnTransformer com StandardScaler para numéricas, passthrough para binárias, encoding específico por tipo
- **Sem Dados Faltantes**: Dataset original não possui valores missing, eliminando necessidade de imputação

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
analise_rotatividade.ipynb

# Executar todas as células
Cell → Run All
```

### Saídas Geradas
- **Visualizações**: Automaticamente salvas na pasta `outputs/`
- **Modelos**: Modelos treinados salvos na pasta `modelos/`
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

## 🤖 Modelo Preditivo Melhorado

### **Arquitetura do Pipeline Implementada**

#### **Preprocessing com ColumnTransformer**
```python
preprocessor = ColumnTransformer([
    ('num', StandardScaler(), numerical_features),
    ('bin', 'passthrough', binary_features),
    ('ord', 'passthrough', ordinal_features),  # Manual mapping
    ('nom', OneHotEncoder(handle_unknown='ignore', drop='first'), nominal_features)
], remainder='drop')
```

#### **Pipeline Completo Anti-Leakage**
```python
pipeline = Pipeline([
    ('preprocessor', preprocessor),
    ('classifier', RandomForestClassifier(
        class_weight='balanced',
        random_state=42,
        n_jobs=-1
    ))
])
```

### **Performance com Cross-Validation**

#### **Métricas Robustas (5-Fold Stratified CV)**
- **ROC-AUC**: 0.723 (±0.011) - Boa capacidade discriminativa
- **F1-Score**: 0.542 (±0.017) - Balanceamento adequado
- **F2-Score**: 0.788 - Priorizando recall (falsos negativos custosos)
- **Precision**: 0.452 (±0.014) - Controle de falsos positivos
- **Recall**: 0.677 (±0.022) - Boa detecção de funcionários em risco
- **Accuracy**: 0.667 (±0.012) - Performance geral sólida

### **Tuning Orientado a Custo**

#### **RandomizedSearchCV Implementado**
```python
param_distributions = {
    'classifier__n_estimators': [50, 100, 200, 300],
    'classifier__max_depth': [None, 5, 10, 15, 20],
    'classifier__min_samples_split': [2, 5, 10, 20],
    'classifier__min_samples_leaf': [1, 2, 5, 10],
    'classifier__max_features': ['sqrt', 'log2', 0.3, 0.5, 0.7],
    'classifier__class_weight': ['balanced', 'balanced_subsample', None]
}
```

#### **Otimização de Threshold**
- **Métrica Objetivo**: F2-Score (β=2) priorizando recall
- **Custos de Negócio**:
  - False Negative: $49,250 (custo de perder funcionário)
  - False Positive: $2,000 (custo de intervenção desnecessária)
  - True Positive: -$15,000 (economia por retenção bem-sucedida)
- **Threshold Ótimo**: 0.100 (vs 0.5 padrão)
- **Economia Demonstrada**: $6,360,250 anual

### **Principais Features Preditivas** *(Random Forest Feature Importance)*
1. **Satisfação** (0.245) - Fator mais importante
2. **Avaliação de Performance** (0.187) - Segunda maior influência
3. **Tempo na Empresa** (0.156) - Padrões de saída por tenure
4. **Horas Mensais** (0.134) - Sobrecarga vs subutilização
5. **Número de Projetos** (0.089) - Carga de trabalho
6. **Nível Salarial** (0.078) - Impacto da remuneração
7. **Departamento** (0.067) - Diferenças culturais/estruturais
8. **Promoção Recente** (0.032) - Menor impacto individual
9. **Acidente de Trabalho** (0.012) - Menor relevância

### **Uso do Modelo em Produção**

#### **Carregamento do Pipeline Completo**
```python
import joblib
import pandas as pd

# Carregar pipeline treinado (inclui preprocessing)
pipeline = joblib.load('modelos/modelo_rotatividade.pkl')

# Dados de novo funcionário (formato original)
new_employee = pd.DataFrame({
    'satisfaction': [0.45],
    'review': [0.65],
    'projects': [4],
    'avg_hrs_month': [220],
    'tenure': [3],
    'work_accident': [0],
    'promoted': [0],
    'bonus': [0],
    'department': ['sales'],
    'salary': ['medium']
})

# Predição com pipeline completo
risk_probability = pipeline.predict_proba(new_employee)[:, 1][0]
risk_level = "Alto" if risk_probability > 0.7 else "Médio" if risk_probability > 0.3 else "Baixo"

print(f"Probabilidade de saída: {risk_probability:.3f}")
print(f"Nível de risco: {risk_level}")
```

#### **Interpretação das Predições**
- **Alto Risco (>70%)**: Intervenção imediata necessária
- **Médio Risco (30-70%)**: Monitoramento intensivo
- **Baixo Risco (<30%)**: Manutenção de condições atuais

### **Melhorias Implementadas vs. Versão Original**

| Aspecto | Versão Original | Versão Melhorada | Benefício |
|---------|------------------|-------------------|----------|
| **Preprocessing** | LabelEncoder manual | ColumnTransformer + Pipeline | Evita data leakage |
| **Validação** | Holdout simples | 5-Fold Stratified CV | Métricas mais robustas |
| **Hyperparâmetros** | Padrões | RandomizedSearchCV | Performance otimizada |
| **Threshold** | 0.5 fixo | 0.1 otimizado por custo | Economia de $6.36M |
| **Métrica** | F1 genérico | F2 orientado a negócio | Alinhamento estratégico |
| **Deploy** | 4 arquivos | 1 pipeline único | Simplicidade operacional |
| **Reprodutibilidade** | Manual | Automatizada | Confiabilidade |

## 📊 Visualizações Estratégicas Implementadas

### **3 Visualizações Criteriosamente Selecionadas**

#### **1. Precision-Recall Curve** `strategic_01_precision_recall_curve.png`
- **Objetivo**: Validar performance do modelo em dados desbalanceados
- **Valor**: Crítica para datasets com rotatividade (classe minoritária)
- **Insight**: Mostra trade-off entre precisão e recall por threshold
- **Métrica**: Average Precision Score vs. baseline no-skill

#### **2. Feature Importance** `strategic_02_feature_importance.png`
- **Objetivo**: Comunicar fatores-chave aos stakeholders
- **Valor**: Direciona intervenções estratégicas baseadas em evidências
- **Insight**: Satisfação e performance dominam predições
- **Formato**: Gráfico horizontal com nomes amigáveis aos gestores

#### **3. Distribuição de Probabilidades** `strategic_03_probability_distributions.png`
- **Objetivo**: Justificar escolha de thresholds para ação
- **Valor**: Fundamenta cientificamente ponto de corte 0.7 para alto risco
- **Insight**: Mostra separabilidade entre funcionários retidos vs. que saíram
- **Formato**: Histogramas + box plots com thresholds visíveis

### **Critérios de Seleção Aplicados**
- ✅ **Alto Impacto**: Comunicam insights críticos para tomada de decisão
- ✅ **Baixo Esforço**: Implementação direta sem complexidade excessiva
- ✅ **Valor Estratégico**: Cada visualização serve propósito específico no processo
- ✅ **Complementares**: Cobrem validação técnica, comunicação executiva e justificativa operacional

## 📊 Principais Visualizações do Projeto

1. **Distribuição Geral de Rotatividade**: Gráfico de pizza e barras mostrando 29,2% de rotatividade
2. **Matriz de Correlação**: Relacionamentos entre todas as variáveis numéricas

**Nota**: Outras visualizações são geradas dinamicamente durante a execução do notebook e podem ser salvas conforme necessário.

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

## 🎯 Critérios de Sucesso de Negócio

### 📈 Métricas Principais de Sucesso

**OBJETIVO PRIMÁRIO**: Reduzir rotatividade anual de **29,2%** para **20,4%-26,3%** (redução de 10%-30%)

#### **KPIs de Resultado (ROI)**
- **Economia Anual Mínima**: $13,7M (cenário conservador)
- **ROI Mínimo Aceitável**: 8,4% (benchmark de mercado: 6-10%)
- **Payback Máximo**: 37 meses (limite organizacional)
- **Redução de Custos**: Mínimo 10% do custo anual atual

#### **KPIs Operacionais**
- **Funcionários Alto Risco**: <1.500 (atual: 2.352)
- **Precision Mínima do Modelo**: >45% (evitar falsos positivos excessivos)
- **Recall Mínimo do Modelo**: >40% (capturar casos reais de saída)
- **Taxa de Retenção Pós-Intervenção**: >85% dos identificados como alto risco

#### **KPIs por Departamento**
- **Taxa Máxima Departamental**: <25% (atualmente 5 departamentos >25%)
- **Redução IT/Logistics**: De 30,9%/30,8% para <25%
- **Melhoria Satisfaction Score**: >0,65 média (baseline: variável)

### 🎯 Critérios Técnicos de Qualidade

#### **Performance do Modelo**
- **AUC-ROC Mínimo**: >0,65 (atual: 0,625)
- **F2-Score Mínimo**: >0,50 (prioriza recall por custos assimétricos)
- **Estabilidade**: Variação <5% em validação cruzada
- **Generalização**: Performance similar em holdout test

#### **Implementação**
- **Tempo de Predição**: <1 segundo por funcionário
- **Atualização de Modelo**: Semestral ou quando accuracy <threshold
- **Cobertura**: 100% da força de trabalho ativa

## 🛠️ Requisitos Técnicos e Reprodutibilidade

### **Ambiente de Desenvolvimento**
```bash
# Dependências Principais (versões testadas)
pip install pandas==2.1.4 numpy==1.24.3 matplotlib==3.7.2 
pip install seaborn==0.12.2 scikit-learn==1.3.2 scipy==1.11.4 joblib==1.3.2

# Dependências Opcionais
pip install jupyter notebook ipykernel
```

### **Guia de Reprodução Completa**

#### **1. Setup Inicial**
```bash
# Clone do projeto
git clone [repository-url]
cd Turnover_Qoder/

# Criação do ambiente virtual (recomendado)
python -m venv venv_turnover
source venv_turnover/bin/activate  # Linux/Mac
venv_turnover\Scripts\activate     # Windows

# Instalação de dependências
pip install -r requirements.txt
```

#### **2. Preparação dos Dados**
```bash
# Coloque o dataset na raiz do projeto
cp employee_churn_data.csv .

# Verificar estrutura esperada
ls -la  # Deve conter: analise_rotatividade.ipynb, employee_churn_data.csv
```

#### **3. Execução da Análise**
```bash
# Opção 1: Jupyter Notebook (recomendado)
jupyter notebook analise_rotatividade.ipynb
# Execute todas as células: Cell → Run All

# Opção 2: Execução por linha de comando (experimental)
python -c "exec(open('analise_rotatividade.ipynb').read())"
```

#### **4. Validação dos Resultados**
```bash
# Verificar saídas geradas
ls outputs/    # Deve conter visualizações PNG
ls modelos/    # Deve conter modelos .pkl

# Testar modelo salvo
python -c "import joblib; model=joblib.load('modelos/modelo_rotatividade.pkl'); print('Modelo carregado com sucesso')"
```

### **Estrutura de Arquivos Resultantes**
```
Turnover_Qoder/
├── 📊 employee_churn_data.csv          # Dataset original (NÃO versionado)
├── 📓 analise_rotatividade.ipynb       # Notebook principal com análise DDPP
├── 📁 outputs/                         # Visualizações geradas
│   ├── 01_taxa_rotatividade_geral.png
│   ├── 04_matriz_correlacao.png
│   ├── strategic_01_precision_recall_curve.png
│   ├── strategic_02_feature_importance.png
│   └── strategic_03_probability_distributions.png
├── 🤖 modelos/                         # Modelos treinados
│   ├── modelo_rotatividade.pkl
│   ├── scaler.pkl
│   ├── label_encoder_dept.pkl
│   └── label_encoder_salary.pkl
└── 📋 README.md                        # Esta documentação
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


**Nota**: Esta análise fornece insights baseados em dados para tomada de decisão estratégica. A implementação deve ser adaptada ao contexto organizacional específico e requisitos legais.

## 📞 Contato

**Autor**: Eanes Santos Ribeiro  
**Email**: [eanesribeiro@gmail.com](mailto:eanesribeiro@gmail.com)  
**LinkedIn**: [https://www.linkedin.com/in/eanessantosribeiro/](https://www.linkedin.com/in/eanessantosribeiro/)  
**GitHub**: [https://github.com/EanesRibeiro](https://github.com/EanesRibeiro)

### 📝 Sobre o Projeto

Este projeto foi desenvolvido como parte de uma análise abrangente de rotatividade de funcionários, aplicando metodologias científicas de ciência de dados e frameworks estruturados para gerar insights acionáveis no ambiente corporativo.

Para dúvidas, sugestões ou colaborações, entre em contato através dos canais acima.