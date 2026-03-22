<p align="center">
  <img src="https://img.shields.io/badge/Status-Finalizado-green?style=for-the-badge" alt="Status: Finalizado"/>
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.11"/>
  <img src="https://img.shields.io/badge/Bibliotecas-Scikit--learn%20|%20TensorFlow%20|%20Keras%20|%20Streamlit-orange?style=for-the-badge" alt="Bibliotecas"/>
</p>

# 📊 Datathon: ONG Passos Mágicos

Este repositório contém o projeto de **análise de dados e modelagem preditiva** desenvolvido para o Datathon da ONG **Passos Mágicos**.

O foco central é utilizar **Inteligência Artificial** para identificar alunos que necessitam de maior apoio educacional e social.

---

## 🎯 O Objetivo

O projeto visa apoiar a tomada de decisão da ONG por meio de modelos de Machine Learning aplicados a indicadores acadêmicos e sociais.

O sistema atua em duas frentes principais:

- 🔄 **Ponto de Virada**  
  Identificar momentos de evolução significativa na trajetória do aluno.

- 🎓 **Indicação de Bolsa**  
  Estimar a probabilidade de elegibilidade para apoio financeiro.

---

## 🚀 Funcionalidades e Modelos

### 🔮 Predição de Ponto de Virada
- **Modelo**: Random Forest (`.pkl`)
- **Fatores analisados**:
  - Desempenho acadêmico
  - Situação psicossocial
  - Continuidade nos estudos
  - Vulnerabilidade social

### 🎓 Predição de Indicação de Bolsa
- **Modelo**: Rede Neural (Keras / TensorFlow)
- **Fatores analisados**:
  - Engajamento
  - Desenvolvimento educacional
  - Permanência
  - Contexto social

---

## 🖥️ Interface

Aplicação web interativa desenvolvida com **Streamlit**, permitindo:

- Simulação de cenários
- Visualização de predições em tempo real

---

## ⚙️ Requisitos

- Python 3.11  
- `pip` atualizado  
- Terminal ou prompt de comando  

---

## 🚀 Instalação

> 💡 Recomendado: utilize ambiente virtual (`venv`)

### 1. Criar o ambiente virtual

```bash
python -m venv venv
