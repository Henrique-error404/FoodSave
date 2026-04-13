# FoodSave AI 🍽️⚠️

Conscientização e Redução do Desperdício de Alimentos com Inteligência Artificial  

---

[![Oracle APEX](https://img.shields.io/badge/Oracle_APEX-Application-F80000?logo=oracle&logoColor=white)](https://apex.oracle.com/)
[![Oracle Database](https://img.shields.io/badge/Oracle_DB-Connected-F80000?logo=oracle&logoColor=white)](https://www.oracle.com/database/)
[![AI Concept](https://img.shields.io/badge/AI-Generative%20%26%20NLP-blueviolet)]()
[![Status](https://img.shields.io/badge/Status-Discontinued-critical)]()

---

## 📌 Sobre o Projeto

O **FoodSave AI** foi idealizado como uma solução para combater o desperdício de alimentos por meio de **Inteligência Artificial integrada ao Oracle APEX**.

A proposta era permitir que usuários registrassem alimentos disponíveis e recebessem sugestões inteligentes de consumo, receitas e alertas antes do vencimento.

⚠️ **Importante:**  
O projeto **não foi concluído na prática** devido a limitações técnicas enfrentadas com o Oracle APEX, especialmente relacionadas a erros constantes em requisições e dificuldades na integração com serviços de IA.

---

## 🎯 Objetivo do Projeto

### Objetivo Principal
- Definir e documentar um componente de IA integrado ao Oracle APEX, incluindo:
  - Caso de uso
  - Dados utilizados
  - Modelo de IA
  - Estratégia de integração com Oracle Database

### Objetivos Específicos
- Definir o problema de IA dentro do contexto do desperdício de alimentos  
- Demonstrar o funcionamento dos componentes principais (mesmo que conceitualmente)  
- Descrever o fluxo de dados entre APEX, banco e IA  
- Escolher e justificar o modelo de IA  

---

## 🧠 Problema de IA

O projeto buscava resolver o seguinte problema:

> **Como reduzir o desperdício de alimentos utilizando recomendações inteligentes baseadas nos itens disponíveis do usuário?**

### Solução proposta:
- Analisar alimentos cadastrados pelo usuário  
- Identificar proximidade de vencimento  
- Sugerir:
  - Receitas
  - Combinações de alimentos
  - Alertas inteligentes  

---

## 🤖 Modelo de IA Proposto

Foi definido o uso de:

- **LLM (Large Language Model)**  
- **NLP (Processamento de Linguagem Natural)**  

### Justificativa:
- Capacidade de interpretar listas de alimentos em linguagem natural  
- Geração de recomendações personalizadas  
- Flexibilidade para diferentes tipos de entrada do usuário  

---

## 📊 Dados Utilizados

### Tipos de dados:
- Lista de alimentos do usuário  
- Datas de validade  
- Categorias (frutas, verduras, carnes, etc.)  

### Origem:
- Inserção manual via APEX  
- (Planejado) integração com APIs externas de receitas  

### Estrutura:
```json
{
  "alimento": "banana",
  "validade": "2026-04-15",
  "categoria": "fruta"
}
