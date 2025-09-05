# Previsão de vendas

Todos os detalhes sobre este projeto segue no relatório técnico. [Clique aqui para abrir o PDF diretamente](docs/relatorio_tecnico.pdf).


# Estrutura

```text
├── data/
│   ├── processed/
│   │   └── processed_dataset.csv
│   └── dataset.csv      
├── docs/
│   ├── relatorio_tecnico.pdf   
│   └── dicionario_de_dados.csv
├── notebooks/
│   ├── analise_exploratoria.ipynb
│   └── modelagem.ipynb
└── README.md
└── requirements.txt

```
# Pipeline de execução do projeto

1. Instale as dependências listadas no arquivo ``requirements.txt`` com o seguinte comando:

     ```bash
   pip install -r requirements.txt
   ```

<br>

2. Certifique-se de que o dataset ``dataset.csv`` esteja na pasta ``data``.
<br>

3. Execute os notebooks com:
   

   ```bash
   jupyter notebook analise_exploratoria.ipynb
   jupyter notebook modelagem.ipynb
   ```