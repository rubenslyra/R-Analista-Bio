# Módulo 01: Fundamentos de R para Bioinformática

## Visão Geral
Este módulo introduz a linguagem R com foco em aplicações de bioinformática forense. Você aprenderá desde os conceitos básicos da linguagem até o uso de pacotes especializados do Bioconductor e técnicas avançadas de visualização de dados genômicos.

**Carga horária estimada:** 20 horas  
**Pré-requisitos:** Nenhum conhecimento prévio de programação necessário

---

## 📚 Aulas

| Aula | Título | Tópicos Principais | Arquivo |
|------|--------|-------------------|---------|
| 01 | Introdução ao R para Bioinformática | Tipos de dados, vetores, matrizes, listas, data frames, importação/exportação | [aulas/01-introducao-r.Rmd](aulas/01-introducao-r.Rmd) |
| 02 | Tidyverse e Manipulação de Dados Forenses | dplyr, tidyr, pipe operator, ggplot2, transformação wide/long | [aulas/02-tidyverse-manipulacao-dados.Rmd](aulas/02-tidyverse-manipulacao-dados.Rmd) |
| 03 | Bioconductor e Pacotes Especializados | Biostrings, GenomicRanges, adegenet, formatos FASTA/VCF/GFF | [aulas/03-bioconductor-pacotes-especializados.Rmd](aulas/03-bioconductor-pacotes-especializados.Rmd) |
| 04 | Visualização Avançada de Dados Genômicos | Eletroferogramas, heatmaps STR, Manhattan plots, temas para laudos | [aulas/04-visualizacao-avancada-genomica.Rmd](aulas/04-visualizacao-avancada-genomica.Rmd) |

---

## 📝 Exercícios e Gabaritos

| Aula | Gabarito | Dataset |
|------|----------|---------|
| 01 | [exercicios/gabarito_aula01.Rmd](exercicios/gabarito_aula01.Rmd) | [datasets/amostras_forenses_aula01.csv](datasets/amostras_forenses_aula01.csv) |
| 02 | [exercicios/gabarito_aula02.Rmd](exercicios/gabarito_aula02.Rmd) | Usa dataset da Aula 01 |
| 03 | [exercicios/gabarito_aula03.Rmd](exercicios/gabarito_aula03.Rmd) | Dados simulados no próprio exercício |
| 04 | [exercicios/gabarito_aula04.Rmd](exercicios/gabarito_aula04.Rmd) | Dados simulados no próprio exercício |

---

## 🎯 Competências Adquiridas

Ao final deste módulo, você será capaz de:

- ✅ Programar em R com sintaxe moderna (tidyverse, pipe nativo)
- ✅ Manipular dados tabulares e biológicos de forma eficiente
- ✅ Utilizar pacotes do Bioconductor para análise genômica
- ✅ Criar visualizações profissionais para relatórios forenses
- ✅ Trabalhar com formatos bioinformáticos padrão (FASTA, VCF, GFF)
- ✅ Aplicar boas práticas de reprodutibilidade e documentação

---

## 🛠️ Pacotes R Utilizados

### Essenciais
```r
install.packages("tidyverse")      # dplyr, ggplot2, tidyr, readr
install.packages("patchwork")      # Composição de gráficos
```

### Bioconductor
```r
BiocManager::install(c(
  "Biostrings",           # Manipulação de sequências
  "GenomicRanges",        # Anotações genômicas
  "BSgenome.Hsapiens.UCSC.hg38",  # Genoma humano referência
  "VariantAnnotation",    # Anotação de variantes
  "adegenet"              # Genética de populações
))
```

---

## ⏭️ Próximo Módulo

Após completar este módulo, prossiga para o **Módulo 02: Fundamentos de Python para Bioinformática**, onde você aprenderá a linguagem Python e suas bibliotecas essenciais (NumPy, Pandas, Biopython) aplicadas à análise forense.

---

## 📖 Recursos Complementares

- [R for Data Science](https://r4ds.hadley.nz/) — Hadley Wickham (gratuito)
- [Bioconductor Workflow](https://www.bioconductor.org/help/workflows/)
- [SWGDAM Guidelines](https://www.swgdam.org/)
- [ggplot2 Cheat Sheet](https://rstudio.github.io/cheatsheets/data-visualization.pdf)