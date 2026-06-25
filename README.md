<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6A5ACD&height=140&section=header&text=Genetic%20Algorithm%20—%20TSP&fontSize=34&fontColor=ffffff&animation=fadeIn&fontAlignY=50&desc=Problema%20do%20Caixeiro%20Viajante%20com%20Algoritmo%20Genético&descSize=15&descAlignY=72&descColor=ffffffcc"/>

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org)

</div>

---

## 📌 Sobre o Projeto

Implementação de um **Algoritmo Genético (AG)** para resolver o clássico **Problema do Caixeiro Viajante (TSP)** — encontrar a rota mais curta que visita cada cidade exatamente uma vez e retorna à origem.

O projeto também compara a eficiência do AG com a abordagem de **força bruta**:

| Abordagem | Complexidade | 10 cidades |
|-----------|-------------|------------|
| Força Bruta | O(n!) | 3.628.800 operações |
| Algoritmo Genético | O(n² · 2ⁿ) | ~102.400 operações |

---

## 🧬 Como funciona o Algoritmo Genético

```
1. 🎲 Geração da população inicial   →  permutações aleatórias de cidades
2. 📏 Avaliação (Fitness)            →  distância euclidiana total da rota
3. 🏆 Seleção                        →  melhores rotas são selecionadas
4. 🔀 Crossover                      →  combinação de duas rotas pai
5. 🔧 Mutação                        →  pequenas trocas aleatórias na rota
6. 🔁 Repetição                      →  até atingir o número de gerações
```

---

## 🛠️ Tecnologias

| Biblioteca | Uso |
|-----------|-----|
| `numpy` | Geração de permutações e cálculos de distância |
| `matplotlib` | Visualização das rotas e cidades |
| `seaborn` | Estilização dos gráficos |

---

## 🚀 Como executar

### Pré-requisitos

```bash
pip install numpy matplotlib seaborn jupyter
```

### Rodando o notebook

```bash
git clone https://github.com/Renatococaf/genetic-algorithm.git
cd genetic-algorithm/ga
jupyter notebook genetic_algorithm.ipynb
```

---

## 📁 Estrutura do Projeto

```
genetic-algorithm/
└── ga/
    └── genetic_algorithm.ipynb   # Notebook principal com a implementação
```

---

<div align="center">

Feito por <a href="https://github.com/Renatococaf">Renatococaf</a>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6A5ACD&height=80&section=footer"/>