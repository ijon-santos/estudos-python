# 🐍 Estudos Avançados em Python

Este repositório contém meus estudos completos de Python, cobrindo desde fundamentos até tópicos avançados como programação funcional, concorrência, otimização, machine learning e engenharia de dados.

## 📚 Estrutura

- **01_python_fundamentos** - Sintaxe, tipos, estruturas de controle, funções, módulos
- **02_python_intermediario** - Comprehensions, geradores, decoradores, closures
- **03_python_avancado** - Programação funcional, POO profunda, concorrência, otimização
- **04_data_science_engenharia** - NumPy, Pandas, Visualização, Estatística
- **05_machine_learning_e_ia** - Scikit-learn, PyTorch, Deep Learning, LLMs
- **06_engenharia_de_dados** - SQL, Big Data, ETL, Pipelines
- **07_algoritmos_e_estruturas_dados** - Listas, árvores, grafos, ordenação, DP
- **08_projetos_praticos** - Aplicações reais integrando múltiplos conceitos

## 🧠 LeetCode por Nível

- **Nível 0** - Nenhum conhecimento
- **Nível 1** - Curioso (já ouviu falar)
- **Nível 2** - Iniciante
- **Nível 3** - Básico
- **Nível 4** - Intermediário
- **Nível 5** - Avançado
- **Nível 6** - Proficiente
- **Nível 7** - Especialista
- **Nível 8** - Mestre
- **Nível 9** - Referência mundial
- **Nível 10** - Pioneiro da área

## 🔧 Como usar

```bash
# Construir a imagem
docker build -f Dockerfile.estudos -t estudos-python:latest .

# Rodar o JupyterLab
docker run -it -p 8889:8888 -v $(pwd):/home/estudos estudos-python:latest

Acesse http://localhost:8889/lab


