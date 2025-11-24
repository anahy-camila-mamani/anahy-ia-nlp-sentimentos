# 🧠 Sistema de Análise de Sentimento e Extração de Aspectos (NLP + IA)

Este projeto consiste no desenvolvimento de um **pipeline completo de NLP** para analisar feedbacks de clientes simulando o contexto de plataformas de delivery.  
A solução utiliza **Modelos Transformer**, técnicas de **Processamento de Linguagem Natural**, e **aprendizado de máquina** para transformar textos não estruturados em insights estratégicos para negócio.

---

## 🎯 Objetivo do Projeto
Criar um sistema capaz de:
- Classificar automaticamente feedbacks como **Positivo**, **Negativo** ou **Neutro**
- Identificar os principais temas abordados pelos clientes (aspectos)
- Gerar insights práticos para tomada de decisão
- Reduzir o tempo gasto por equipes na análise manual de comentários

---

## 🚀 Tecnologias Utilizadas
- **Python**
- **Pandas**
- **Scikit-learn**
- **NLTK**
- **SpaCy**
- **Hugging Face Transformers**
- **Matplotlib**
- **Git/GitHub**

---

## 🧩 Pipeline do Projeto

### 1. Coleta e Preparação dos Dados
- Importação de dados simulados de reviews
- Limpeza textual: remoção de stopwords, normalização, tokenização
- Aplicação de técnicas de pré-processamento para modelos baseados em Transformers

### 2. Modelagem – Classificação de Sentimento
- Treinamento de um modelo baseado em **Transformers / BERT**
- Criação de pipeline de inferência
- Avaliação com métricas: precisão, recall, F1-score

📌 **Resultado final:**  
O modelo atingiu um **F1-Score de 91%**, garantindo consistência na classificação automática dos comentários.

### 3. Extração de Aspectos (Aspect-Based Sentiment Analysis)
- Identificação dos principais temas mencionados pelos usuários
- Uso de:
  - Topic Modeling (LDA ou NMF)  
  - Zero-shot classification com LLMs  
  - Name Entity Recognition (opcional)  

📌 **Insight chave:**  
65% das reclamações estavam relacionadas a **logística** (atrasos, rota, comunicação do entregador).

### 4. Geração de Insights
- Resumo automático dos feedbacks
- Heatmap de tópicos e volume de reviews
- Análises combinadas para entendimento profundo do comportamento do usuário

---

## 📊 Resultados Principais

| Componente              | Resultado |
|------------------------|-----------|
| F1-score Classificação | **91%**   |
| Tempo de triagem       | **-80%**  |
| Reclamações mapeadas   | 65% relacionadas à logística |

---

├── data/ # Dados brutos e tratados (simulados)
├── notebooks/ # Notebook principal do projeto
├── src/ # Scripts Python (funções e pipelines)
├── requirements.txt # Dependências para reprodução
└── README.md # Documentação principal

---


## ▶️ Como Executar o Projeto

### 1. Clone este repositório:

git clone https://github.com/anahy-camila-mamani/anahy-ia-nlp-sentimentos


### 2. Instale as dependências:

pip install -r requirements.txt


### 3. Execute o notebook:
Abra o arquivo dentro da pasta **/notebooks** e execute célula por célula.

---

## 📌 Próximas melhorias (Roadmap)
- Criar API com FastAPI para disponibilizar o modelo
- Criar painel interativo com Streamlit
- Treinar versão final com dataset maior
- Implementar mecanismo de feedback do usuário ao modelo

---

## 👩‍💻 Autora
**Anahy Camila Aruquipa Mamani**  
Estudante de ADS | Focada em IA Generativa, Machine Learning e NLP  
📌 LinkedIn: https://linkedin.com/in/anahy-camila-aruquipa  
📌 E-mail: **anahcamila198@gmail.com**

---
## 📁 Estrutura do Projeto

