# Módulo 02: Fundamentos de Python para Bioinformática

## Visão Geral
Este módulo introduz a linguagem Python com foco em aplicações de bioinformática forense. Você aprenderá desde a sintaxe básica até o uso de bibliotecas especializadas como Biopython, Pandas e scikit-learn para análise de dados biológicos e forenses.

**Carga horária estimada:** 20 horas  
**Pré-requisitos:** Módulo 01 (R) recomendado, mas não obrigatório

---

## 📚 Aulas

| Aula | Título | Tópicos Principais | Arquivo |
|------|--------|-------------------|---------|
| 01 | Introdução ao Python para Bioinformática | Tipos de dados, listas, dicionários, strings, Pandas básico | [aulas/01-introducao-python.ipynb](aulas/01-introducao-python.ipynb) |
| 02 | NumPy e Pandas Avançado | Arrays, vetorização, groupby, merge, pivot tables | *em breve* |
| 03 | Biopython e Manipulação de Sequências | Seq objects, alinhamentos, BLAST, formatos FASTA/VCF | *em breve* |
| 04 | Visualização Científica e Machine Learning | Matplotlib, Seaborn, scikit-learn básico | *em breve* |

---

## 📝 Exercícios e Gabaritos

| Aula | Gabarito | Dataset |
|------|----------|---------|
| 01 | [exercicios/gabarito_aula01.ipynb](exercicios/gabarito_aula01.ipynb) | Dados simulados no próprio exercício |
| 02 | *em breve* | — |
| 03 | *em breve* | — |
| 04 | *em breve* | — |

---

## 🎯 Competências Adquiridas

Ao final deste módulo, você será capaz de:

- ✅ Programar em Python com sintaxe moderna e pythonica
- ✅ Manipular dados tabulares e biológicos com Pandas e NumPy
- ✅ Processar sequências de DNA/RNA/proteínas com Biopython
- ✅ Criar visualizações científicas profissionais
- ✅ Aplicar algoritmos básicos de machine learning em dados forenses
- ✅ Automatizar pipelines de análise bioinformática

---

## 🛠️ Bibliotecas Python Utilizadas

### Essenciais
```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### Bioinformática
```bash
pip install biopython pysam scikit-learn plotly
```

### Ambiente Recomendado
```bash
conda create -n bioforense python=3.11
conda activate bioforense
conda install numpy pandas biopython matplotlib seaborn jupyter scikit-learn
```

---

## ⏭️ Próximo Módulo

Após completar este módulo, prossiga para o **Módulo 03: Análise Forense de Dados Biológicos**, onde você aplicará R e Python integrados em estatística forense, validação de métodos e classificação de amostras.

---

## 📖 Recursos Complementares

- [Python for Biologists](https://pythonforbiologists.com/) — Martin Jones
- [Biopython Tutorial](https://biopython.org/wiki/Documentation)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [SWGDAM Guidelines](https://www.swgdam.org/)