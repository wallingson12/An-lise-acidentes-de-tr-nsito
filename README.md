# 🚦 Análise de Acidentes de Trânsito em Porto Alegre

Este projeto realiza uma análise exploratória, estatística e preditiva sobre **acidentes de trânsito** no município de **Porto Alegre**, utilizando dados públicos. O objetivo é identificar **padrões temporais, espaciais e de gravidade** para apoiar a formulação de políticas públicas e ações de prevenção.

---

## 📑 Estrutura do Projeto

- **Contexto e Objetivo**: Introdução ao problema da segurança viária em Porto Alegre e objetivos do projeto.
- **Análises Descritivas**: Evolução temporal dos acidentes, tipos de acidentes e veículos envolvidos.
- **Análises Espaciais**: Mapas de calor e clusters de acidentes por região da cidade.
- **Estatística Inferencial**: Aplicação do teste Qui-Quadrado para avaliar a associação entre ruas e horários.
- **Análises Preditivas**: Desenvolvimento de um modelo para prever se haverá feridos nos acidentes.
- **Conclusão e Recomendações**: Síntese dos principais achados e sugestões de ações para reduzir acidentes.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- [Pandas](https://pandas.pydata.org/) – Manipulação e análise de dados.
- [NumPy](https://numpy.org/) – Suporte numérico para operações vetoriais.
- [Matplotlib](https://matplotlib.org/) e [Seaborn](https://seaborn.pydata.org/) – Visualizações gráficas.
- [Folium](https://python-visualization.github.io/folium/) – Mapas interativos para análise espacial.
- [SciPy](https://scipy.org/) – Estatísticas e análise de dados (teste Qui-Quadrado).
- **Scikit-Learn** – Modelagem preditiva e avaliação de modelos de machine learning.

---

## 📊 Principais Resultados

- **Crescimento de acidentes** de 2020 a 2023, com uma leve queda observada em 2024.
- **Colisão** e **abalroamento** são os tipos de acidente mais frequentes.
- **Automóveis e motocicletas** são os veículos mais envolvidos em acidentes, seguidos por caminhões.
- **Horários de pico (manhã e tarde)** apresentam maiores concentrações de acidentes.
- As avenidas **Ipiranga, Protásio Alves, Bento Gonçalves e Sertório** são identificadas como as **mais críticas** para acidentes.
- O **teste Qui-Quadrado** revelou uma associação significativa entre **ruas e horários** de acidentes.
- O **modelo preditivo** desenvolvido pode prever a severidade dos acidentes, auxiliando na alocação de recursos de fiscalização.

---

## 🧭 Recomendações

1. **Fiscalização Inteligente**: Intensificar o monitoramento nos horários de pico (manhã e tarde), onde a incidência de acidentes é mais alta.
2. **Melhoria na Infraestrutura Viária**: Focar na melhoria da sinalização, controle de velocidade e iluminação nas avenidas críticas (Ipiranga, Protásio Alves, etc.).
3. **Campanhas Educativas**: Desenvolver campanhas de conscientização para motoristas de **automóveis e motocicletas**, os grupos mais frequentemente envolvidos nos acidentes.
4. **Gestão Baseada em Dados**: Usar modelos de previsão de acidentes para otimizar a alocação de recursos de fiscalização e intervenção nas áreas mais críticas.
5. **Exploração de Boas Práticas**: Analisar as ruas com menores ocorrências de acidentes e tentar replicar essas boas práticas em outras áreas da cidade.

---

## 📂 Estrutura de Arquivos

```plaintext
📦 analise-acidentes-transito
┣ 📜 Análise de acidentes.ipynb    # Notebook principal com a análise
┣ 📜 Visualização.pdf             # Exportação de visualizações gráficas
┣ 📜 README.md                    # Este arquivo
┗ 📂 dados                         # (opcional) arquivos CSV de entrada


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
