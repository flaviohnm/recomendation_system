# Sistema de Recomendacao de Livros

Este repositório contém um notebook Jupyter que implementa um sistema de recomendação de livros utilizando técnicas de Machine Learning. O objetivo é fornecer recomendações personalizadas com base em dados de avaliações e preferências dos usuários.

## Conteúdo
- **`recomendation_system.ipynb`**: Contém o código e explicação passo a passo da implementação do sistema de recomendação.
- **`data/`**: Pasta contendo os conjuntos de dados utilizados no treinamento e teste do modelo.
- **`requirements.txt`**: Lista de dependências necessárias para a execução do notebook.

## Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Scikit-Learn
- Surprise (Biblioteca para Sistemas de Recomendação)
- Matplotlib / Seaborn (para visualização de dados)

## Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/flaviohnm/recomendation_system.git
   cd recomendation_system
   ```
2. Crie um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
4. Inicie o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Abra e execute o `recomendation_system.ipynb`.

## Fontes de Dados
Os dados utilizados neste projeto foram obtidos de fontes abertas, como o [Goodreads Dataset](https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home) ou o [Book-Crossing Dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/).

## Contribuição
Fique à vontade para contribuir com melhorias no código, correção de bugs ou adição de novas funcionalidades! Basta abrir um Pull Request.

## Licença
Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

