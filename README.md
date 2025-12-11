# Resolução de Sistemas Lineares

Este repositório apresenta a implementação e análise de dois métodos clássicos para resolução de sistemas lineares:

* **Decomposição de Cholesky**
* **Fatoração LU**

O conteúdo é apresentado em dois notebooks independentes, contendo explicações teóricas, deduções matemáticas e implementações práticas em Python.

---

## Conteúdo dos Notebooks

### 1. Decomposição de Cholesky

O notebook **cholesky.ipynb** inclui:

* Revisão teórica sobre matrizes simétricas definidas positivas
* Dedução da decomposição ( A = LL^T )
* Implementação passo a passo do algoritmo
* Aplicação da decomposição para resolver ( Ax = b )
* Verificação de estabilidade e tempo de execução
* Comparação com `numpy.linalg.cholesky`

### 2. Fatoração LU

O notebook **fatoracao_lu.ipynb** inclui:

* Fundamentos da decomposição LU
* Derivação matricial
* Implementação manual das matrizes **L** e **U**
* Resolução do sistema usando substituição direta e retroativa
* Comparação com `scipy.linalg.lu`
* Demonstração de casos onde pivotamento é necessário

---

### Google Colab

Os notebooks podem ser enviados diretamente para o Colab, sem necessidade de instalação local.

