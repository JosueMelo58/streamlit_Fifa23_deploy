# ⚽📊 Análise de Dados da FIFA23 (2017-2023)

## 🎯 Objetivo
Analisar um conjunto de dados de **+17.000 jogadores profissionais** para extrair insights sobre:
- 🔍 Tendências de desempenho por posição
- 💰 Valor de mercado e relações contratuais
- 📈 Evolução de habilidades ao longo do tempo
- 🏆 Comparativo entre clubes e ligas

_Dados incluem:_ características demográficas, métricas físicas, estatísticas de jogo, e histórico de contratos.

---

## 🛠 Stack Tecnológica
| Tecnologia | Repositório | Uso Principal |
|------------|-------------|---------------|
| <img src="https://img.icons8.com/color/48/python.png" width=20> **Python 3.12.7** | [github.com/python/cpython](https://github.com/python/cpython) | Processamento de dados |
| <img src="https://streamlit.io/images/brand/streamlit-mark-color.svg" width=20> **Streamlit 1.40.1** | [github.com/streamlit/streamlit](https://github.com/streamlit/streamlit) | Dashboard web |
| <img src="https://pandas.pydata.org/static/img/pandas_secondary.svg" width=20> **Pandas 2.2.3** | [github.com/pandas-dev/pandas](https://github.com/pandas-dev/pandas) | Manipulação de dados |



## 📦 Requirements
Para executar o projeto, instale as dependências abaixo:

```bash
python==3.12.7
streamlit==1.40.1
pandas==2.2.3
```

Instale via requirements.txt:
```bash
pip install -r requirements.txt
```
## 📂 Estrutura de Arquivos
```shell
streamlit_Fifa23_deploy/
├── 📁 datasets/
│ └── 📄 CLEAN_FIFA23_official_data.csv # Dados brutos
├── 📁 pages/
│ ├── 📄 2_🏃_players.py # Análise individual
│ └── 📄 3_🔵_teams.py # Comparativo de clubes
├── 📄 1_🏠_home.py # Landing page
```
## 🚀 Execução do Sistema

# Clone o repositório (substitua pela sua URL)
```bash
git clone https://github.com/JosueMelo58/streamlit_Fifa23_deploy
```
# Inicie o servidor Streamlit
```bash
streamlit run 1_🏠_home.py
```
