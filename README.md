# Análise de Esquizofrenia com Redes Neurais em Grafos (GNN) usando PyTorch Geometric

## Descrição do Projeto
Este projeto explora o uso de **Graph Neural Networks (GNNs)** com **PyTorch Geometric** para analisar um conjunto de dados de pacientes que podem ser esquizofrênicos ou não. O objetivo é utilizar a estrutura de grafo para modelar as relações entre os pacientes com base em suas características e identificar padrões que possam auxiliar no diagnóstico e no entendimento da doença.

## Tecnologias Utilizadas
- **Python**
- **PyTorch**
- **PyTorch Geometric**
- **Pandas**
- **NumPy**
- **Scikit-Learn**
- **NetworkX**

## Estrutura do Projeto
- **GNN_esquizofrenia.ipynb**: Notebook principal onde o modelo GNN é treinado e avaliado.
- **schizophrenia_dataset.csv**: Arquivo onde os dados de pacientes estão armazenados.
- **utils.py**: Funções auxiliares para processar os dados e construir o grafo.

## Objetivos do Projeto
- Criar um grafo a partir dos dados tabulares dos pacientes.
- Treinar um modelo de GNN para classificar pacientes entre esquizofrênicos e não-esquizofrênicos.
- Explorar o impacto das conexões no grafo e a influência das features dos nós na classificação.
- Analisar os embeddings gerados para extrair insights sobre a doença.

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/raphaelp-silva/GNN_Pytorch_geometric.git
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install torch torchvision torchaudio torch-geometric pandas numpy scikit-learn networkx matplotlib
   ```
3. Execute o notebook `GNN_esquizofrenia.ipynb` em um ambiente Jupyter Notebook ou Google Colab.

## Resultados e Insights
Os resultados preliminares mostram que a abordagem de GNN consegue capturar padrões nos dados e tem potencial para auxiliar no entendimento da esquizofrenia. No entanto, desafios como overfitting e qualidade dos dados ainda precisam ser trabalhados para melhorar a capacidade de generalização do modelo.

O projeto está em desenvolvimento e ainda não foi finalizado, portanto os resultados obtidos até agora são preliminares

## Melhorias Futuras
- Refinar a construção do grafo para melhor representar relações clínicas.
- Testar diferentes arquiteturas de GNN, como **GraphSAGE** e **GAT (Graph Attention Networks)**.
- Melhorar a generalização do modelo para novos dados.
- Explorar a interpretação dos embeddings gerados pelo modelo.

## Contribuições
Sugestões e contribuições são bem-vindas! Caso tenha interesse, abra uma issue ou envie um pull request.

---
Desenvolvido por **Raphael da Silva** 🚀

