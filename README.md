# 📊 Challenge Alura - TelecomX

**Análise de Evasão de Clientes em Telecomunicações**  
*por Lucas Nathan Consolo*

## 🏆 Certificação Alura ONE
<div align="center">
  <a href="https://cdn3.gnarususercontent.com.br/4752-challenge/%5BBR%5D%20Textos%20e%20Imagens/Aula%203%20-%20Entrega%20do%20desafio/Imagens/imagem%20da%20badge.png">
    <img src="https://cdn3.gnarususercontent.com.br/4752-challenge/%5BBR%5D%20Textos%20e%20Imagens/Aula%203%20-%20Entrega%20do%20desafio/Imagens/imagem%20da%20badge.png" width="200" alt="Badge Alura">
  </a>
  <br>
  <a href="https://github.com/Consolucas/ChallengeAlura_TelecomX_II/blob/main/Challenge%20Telecom%20X%20analise%20de%20evasao%20de%20clientes%20-%20Parte%202.pdf">
    <img src="https://img.shields.io/badge/📄_Ver_Certificado_Completo-FF0000?style=for-the-badge&logo=pdf&logoColor=white" alt="Certificado PDF">
  </a>
  <br>
  <img src="https://img.shields.io/badge/Concluído-Agosto_2025-00C86F?style=flat-square" alt="Data">
  <img src="https://img.shields.io/badge/Carga_Horária-4h-0056D3?style=flat-square" alt="Carga Horária">
</div>

---

## 📌 Metodologia do Projeto

O projeto seguiu uma **abordagem estruturada de Ciência de Dados**, dividida nas seguintes etapas:

1. **Coleta e Pré-processamento de Dados**
   - Limpeza de dados e tratamento de valores ausentes.
   - Transformação de variáveis categóricas em dummies.
   - Balanceamento de classes com **SMOTE** e **Random Oversampling** para lidar com desbalanceamento entre clientes ativos e evadidos.

2. **Análise Exploratória de Dados (EDA)**
   - Investigação da distribuição das variáveis e correlações.
   - Visualização de padrões com **boxplots, scatter plots e histogramas**.
   - Identificação de possíveis relações entre variáveis e evasão.

3. **Modelagem Preditiva**
   - **Regressão Logística:** modelo linear interpretável, utilizado para entender a influência das variáveis sobre a evasão.
   - **Random Forest:** modelo baseado em árvores, robusto para capturar relações não lineares e interações complexas.
   - Avaliação de desempenho com **Acurácia, Precision, Recall, F1-score** e **Matriz de Confusão**.

4. **Análise de Importância das Variáveis**
   - Identificação das variáveis mais relevantes em cada modelo.
   - Comparação entre modelos para validar consistência dos fatores preditivos.

5. **Geração de Insights e Estratégias**
   - Transformação dos resultados em recomendações de retenção de clientes.
   - Foco em variáveis que impactam diretamente a decisão de churn, como tempo de contrato, tipo de contrato, gastos e serviços digitais.

---

## 🛠 Ferramentas e Tecnologias

- **Linguagem:** Python 3.11  
- **Bibliotecas:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `imblearn`  
- **Ambiente:** Jupyter Notebook  
- **Controle de Versão:** Git / GitHub  

---

