# 🎵 Spotify Music Analysis

Análise exploratória de dados de 114.000 músicas do Spotify, 
investigando padrões de popularidade, energia e "felicidade" 
entre diferentes gêneros musicais.

## 📊 Análises e Insights

### 1. Distribuição por Gênero
O dataset é **perfeitamente balanceado**: todos os gêneros têm 
exatamente 1.000 músicas, garantindo comparações justas.

### 2. Gêneros Mais Populares
**pop-film e k-pop** lideram em popularidade média, mostrando 
o alcance global da música de cinema e do pop coreano. 
Sertanejo e brazil aparecem no top 15 — boa representação 
brasileira no cenário mundial.

### 3. Energia vs Dançabilidade
Músicas com **alta energia (>0.6) e alta dançabilidade (>0.6)** 
tendem a ser mais populares. Existe uma correlação positiva 
clara entre as duas dimensões.

### 4. Felicidade Musical por Gênero
**Salsa e forró** são os gêneros mais "felizes" (maior valência), 
enquanto **sleep e dubstep** são os mais melancólicos. 
Música latina e brasileira domina o ranking de alegria.

### 5. Gêneros Brasileiros em Detalhes
Entre os gêneros brasileiros:
- 🏆 **Sertanejo** é o mais popular globalmente
- 💃 **Forró** lidera em dançabilidade e alegria
- 🎭 **Samba** é o segundo mais alegre, mas menos consumido fora do Brasil


## 📁 Estrutura do Projeto
```
spotify-analysis/
│
├── data/
│   └── dataset.csv        # Dataset original do Kaggle
├── notebooks/
│   └── analise.ipynb      # Análise exploratória completa
└── README.md
```

## 🛠️ Tecnologias Utilizadas

- Python 3.11
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📦 Como Executar
```bash
# Clone o repositório
git clone https://github.com/imgustafson/spotify-analysis.git
cd spotify-analysis

# Instale as dependências
pip install pandas matplotlib seaborn jupyter

# Abra o notebook
jupyter notebook notebooks/analise.ipynb
```

## 📌 Dataset

[Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) — disponível no Kaggle.

---
## 👩‍💻 Sobre

Desenvolvido por **Isabella Macedo Gustafson**, estudante de Bacharelado em Matemática Computacional na Universidade Federal Fluminense. 
(Rio das Ostras, RJ)

