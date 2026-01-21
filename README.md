# Otimização de Cronograma de Manutenção Offshore com Machine Learning

## 📌 Visão Geral
Este projeto aplica técnicas de **Machine Learning** para apoiar o **planejamento e replanejamento de campanhas de manutenção offshore**, com foco na **previsão de atrasos** e na **simulação de decisões operacionais**.

O objetivo não é substituir o engenheiro de planejamento, mas **suportar decisões críticas** antes da execução do cronograma.

---

## 🎯 Problema de Negócio
Cronogramas de manutenção offshore frequentemente sofrem atrasos devido a:
- Clima adverso
- Falhas logísticas (helicóptero, embarcações, materiais)
- Liberação operacional
- Dependências excessivas entre atividades
- Alocação inadequada de recursos

Esses fatores impactam diretamente **custo, segurança e disponibilidade da unidade**.

---

## 🧠 Abordagem
O projeto foi estruturado em quatro etapas principais:

1. **Construção de Dataset Realista**
   - Dados simulados com lógica operacional offshore
   - Variáveis de planejamento, execução e fatores externos

2. **Análise Exploratória de Dados (EDA)**
   - Identificação dos principais fatores de atraso
   - Avaliação do impacto de clima, logística, dependências e recursos

3. **Modelagem de Machine Learning**
   - **Classificação:** prever se uma atividade vai atrasar ou não
   - **Regressão:** prever quantos dias de atraso são esperados

4. **Simulação de Replanejamento**
   - Avaliação do impacto de decisões como:
     - Aumento de recursos
     - Redução de dependências
     - Cenário operacional ideal

---

## 🛠️ Tecnologias Utilizadas
- Python  
- Pandas / NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 📊 Principais Insights
- Clima adverso e logística são os **principais drivers de atraso**
- Reduzir dependências no cronograma gera mais impacto do que apenas aumentar recursos
- Recursos ajudam, mas não compensam falhas operacionais
- A integração entre planejamento e operação é essencial para reduzir atrasos

---

## 🚀 Resultados
- Modelo capaz de indicar **probabilidade de atraso por atividade**
- Estimativa do **impacto em dias no cronograma**
- Simulações que apoiam decisões de replanejamento antes da execução

---

## 📈 Aplicações Práticas
- Planejamento de campanhas offshore
- Apoio à tomada de decisão gerencial
- Análise de risco de cronograma
- Integração futura com MS Project, Primavera P6 ou Power BI

---

## 👤 Autor
Marcus Brito  
Engenharia | Planejamento | Data & Machine Learning
