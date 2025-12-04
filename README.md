# 📊 Predição de Evasão Escolar – TCC

Repositório desenvolvido como parte do Trabalho de Conclusão de Curso de Adalberto Soares Oliveira.  
O projeto apresenta uma análise aprofundada sobre os fatores associados à evasão escolar, com foco na região Centro-Oeste de Minas Gerais, utilizando microdados do Censo Escolar e técnicas de aprendizado de máquina.

## 📌 Objetivo do Projeto

O propósito central deste repositório é disponibilizar o código responsável por:

- Processar e limpar os microdados do Censo Escolar.  
- Gerar análises estatísticas, correlações e visualizações.  
- Treinar modelos preditivos (Logistic Regression e Random Forest) para identificar padrões relacionados à evasão escolar.  
- Comparar os resultados obtidos entre diferentes escalas: Brasil, estados e municípios do Centro-Oeste de MG.  
- Produzir gráficos interpretáveis e métricas para subsidiar a tomada de decisão de gestores educacionais.

O código-fonte principal encontra-se no arquivo `tcc - adalberto.py`.

## 🧠 Tecnologias e Bibliotecas

- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Ftfy  
- SciPy  

## 🗂️ Estrutura do Pipeline

1. Carregamento das bases  
2. Tratamento dos dados  
3. Filtragem do Centro-Oeste de Minas Gerais  
4. Seleção das variáveis e identificação dos alvos  
5. Heatmaps de correlação  
6. Treinamento dos modelos  
7. Gráficos de importância e distribuição  
8. Comparação Brasil × Centro-Oeste MG  

## 📁 Estrutura do Repositório

```
predicao-evasao-escolar-tcc/
│
├── tcc - adalberto.py
├── README.md
├── dados/
└── imagens/
```

## 🚀 Como Executar

```
pip install pandas numpy seaborn matplotlib scikit-learn scipy ftfy
python "tcc - adalberto.py"
```

## 🎯 Resultados Esperados

- Correlações por escala  
- Boxplots das variáveis  
- Importância das variáveis  
- Comparação final entre Brasil e Centro-Oeste MG  
- Avaliações completas dos modelos  

## 🛠️ Código-Fonte

Repositório: https://github.com/soaresAdalberto/predicao-evasao-escolar-tcc

## 📌 Autor

**Adalberto Soares Oliveira**
