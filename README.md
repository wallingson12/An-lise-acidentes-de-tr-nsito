# 🚦 Análise de Acidentes de Trânsito em Porto Alegre

Este projeto realiza uma análise exploratória, estatística e preditiva sobre acidentes de trânsito no município de **Porto Alegre**, utilizando dados públicos.  
O objetivo é identificar **padrões temporais, espaciais e de gravidade** para apoiar a formulação de políticas públicas e ações de prevenção.

---

## 📑 Estrutura do Projeto

- **Contexto e Objetivo**: introdução ao problema da segurança viária em Porto Alegre.  
- **Análises Descritivas**: evolução temporal, tipos de acidentes, veículos envolvidos.  
- **Análises Espaciais**: mapas de calor e clusters de acidentes por região.  
- **Estatística Inferencial**: teste Qui-Quadrado para avaliar associação entre ruas e horários.  
- **Análises Preditivas**: modelo para prever severidade (UPS) dos acidentes.  
- **Conclusão e Recomendações**: síntese dos principais achados e ações sugeridas.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- [Pandas](https://pandas.pydata.org/) – manipulação e análise de dados  
- [NumPy](https://numpy.org/) – suporte numérico  
- [Matplotlib](https://matplotlib.org/) e [Seaborn](https://seaborn.pydata.org/) – visualizações  
- [Folium](https://python-visualization.github.io/folium/) – mapas interativos  
- [SciPy](https://scipy.org/) – estatística (Qui-Quadrado)  

---

## 📊 Principais Resultados

- Crescimento de acidentes entre 2020 e 2023, com pequena queda em 2024.  
- **Colisão e abalroamento** = tipos mais frequentes.  
- **Automóveis e motos** concentram a maioria dos casos.  
- **Horários de pico (manhã e tarde)** = maiores concentrações.  
- Ruas críticas: **Ipiranga, Protásio Alves, Bento Gonçalves e Sertório**.  
- Teste Qui-Quadrado confirmou que o risco de acidentes varia conforme **rua e horário**.  
- Modelo preditivo indica possibilidade de prever a severidade do acidente.  

---

## 🧭 Recomendações

1. Intensificar **fiscalização** em horários de pico.  
2. Melhorar **infraestrutura viária** em avenidas críticas.  
3. Campanhas educativas voltadas a **motoristas de carros e motos**.  
4. Utilizar modelos de previsão para **otimizar recursos de fiscalização**.  
5. Explorar **boas práticas de ruas com menos acidentes**.  

---

## 📂 Estrutura de Arquivos
📦 analise-acidentes-transito
┣ 📜 Análise de acidentes.ipynb # Notebook principal com a análise
┣ 📜 Visualização.pdf # Export de visualizações
┣ 📜 README.md # Este arquivo
┗ 📂 dados # (opcional) arquivos CSV de entrada


---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/analise-acidentes-transito.git
   cd analise-acidentes-transito

2. Instale as dependências:
pip install -r requirements.txt

3. jupyter notebook "Análise de acidentes.ipynb"

✅ Conclusão

Este projeto mostra que os acidentes de trânsito não são eventos aleatórios.
Eles seguem padrões claros de tempo, espaço e gravidade.
Compreender esses padrões é essencial para reduzir acidentes, salvar vidas e tornar a mobilidade urbana mais segura.

👨‍💻 Desenvolvido em Python para fins acadêmicos e de ciência de dados.

---

👉 Esse README já está pronto para o GitHub.  
Quer que eu também monte um **requirements.txt** com as libs que você usou, para acompanhar o README?

