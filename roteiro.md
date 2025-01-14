# Roteiro: Designing Machine Learning Systems

## **Capítulo 1: Overview of Machine Learning Systems**

### **Objetivo:**
Introduzir os conceitos fundamentais e os desafios dos sistemas de aprendizado de máquina (ML) em produção.

### **Destaques:**

- **Quando usar ML:**
  - Resolver problemas com padrões complexos.
  - Fazer predições a partir de dados existentes.
  - Operar em larga escala.

- **Componentes de um sistema de ML:**
  - Algoritmos são apenas uma pequena parte do sistema.
  - Incluem requisitos de negócios, infraestrutura, dados e interfaces.

- **Desafios de produção:**
  - Diferenças em relação à pesquisa, como latência, escalabilidade e requisitos de stakeholders.

---

## **Capítulo 2: Introduction to Machine Learning Systems Design**

### **Objetivo:**
Apresentar uma abordagem iterativa para projetar sistemas de ML confiáveis e escaláveis.

### **Destaques:**

- **Objetivos de negócios e ML:**
  - Alinhar requisitos de negócios com objetivos do sistema de ML.
  - Definir métricas que representem sucesso para todas as partes interessadas.

- **Requisitos para sistemas de ML:**
  - **Confiabilidade:** Garantir funcionamento consistente.
  - **Escalabilidade:** Suportar crescimento de dados e usuários.
  - **Manutenção:** Facilidade para atualizar e monitorar.

- **Processo iterativo:**
  - Ciclo de definição de problemas, experimentação, avaliação e iteração.

---

## **Capítulo 3: Data Engineering Fundamentals**

### **Objetivo:**
Cobrir fundamentos de engenharia de dados, desde fontes até processamento, para sustentar sistemas de ML.

### **Destaques:**

- **Fontes e formatos de dados:**
  - Dados estruturados e não estruturados.
  - Formatos como JSON, CSV e bases relacionais.

- **Modelos de dados:**
  - Relacional e NoSQL.

- **Processamento de dados:**
  - ETL (Extrair, Transformar e Carregar) e processamento em lote ou streaming.

- **Desafios:**
  - Garantir qualidade e escalabilidade.

---

## **Capítulo 4: Training Data**

### **Objetivo:**
Explorar estratégias para obter, rotular e preparar dados de treinamento de alta qualidade.

### **Destaques:**

- **Amostragem de dados:**
  - Métodos probabilísticos e não probabilísticos para garantir representatividade.

- **Rotulagem:**
  - Labels manuais, naturais e soluções para falta de rótulos.

- **Problemas comuns:**
  - Desbalanceamento de classes e como lidar com isso.

- **Augmentação de dados:**
  - Transformações e síntese para expandir conjuntos de treinamento.

---

## **Capítulo 5: Feature Engineering**

### **Objetivo:**
Abordar técnicas de criação de características (features) que maximizem o desempenho do modelo.

### **Destaques:**

- **Features projetadas vs. aprendidas:**
  - Projetadas com expertise no domínio.
  - Aprendidas automaticamente por redes neurais.

- **Operações comuns:**
  - Gerenciar valores ausentes, escalonamento e codificação.

- **Evitar vazamento de dados:**
  - Prevenir contaminação entre treino e teste.

- **Generalização:**
  - Criar features que funcionem bem em novos dados.


