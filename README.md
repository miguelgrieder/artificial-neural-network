# Artificial Neural Network Project

Este repositório contém a implementação de uma Rede Neural Artificial (ANN) utilizando dados de exemplos para aprendizado supervisionado.

## Estrutura do Repositório

- `main.ipynb`: Notebook principal com a implementação da rede neural.
- `diabetes.csv`: Conjunto de dados relacionado a diagnósticos de diabetes.
- `housing.csv`: Conjunto de dados sobre habitação.
- `iris.csv`: Conjunto de dados para classificação de flores.
- `.gitignore`: Arquivo para ignorar arquivos desnecessários no controle de versão.
- `requirements.txt`: Arquivo contendo as bibliotecas necessárias para a execução

## Pré-requisitos

Antes de iniciar, certifique-se de ter as ferramentas necessárias instaladas:

- Python 3.7 ou superior
- Jupyter Notebook
- As bibliotecas listadas no arquivo `requirements.txt`

Instale as bibliotecas com o comando:

```bash
pip install -r requirements.txt
```

## Como Executar

Siga os passos abaixo para configurar e executar o projeto:

1. **Clone o repositório**
   Baixe o código-fonte do repositório para o seu computador:

   ```bash
   git clone https://github.com/miguelgrieder/artificial-neural-network.git
   ```

2. **Configure o ambiente**
   Certifique-se de ter o Python 3.7 ou superior instalado.

3. **Instale as dependências**
   Instale as bibliotecas necessárias listadas no arquivo `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

   Ou instale manualmente as bibliotecas necessárias:

   ```bash
   pip install numpy pandas scikit-learn matplotlib tensorflow
   ```

4. **Prepare os dados**
   Certifique-se de que os arquivos de dados (`diabetes.csv`, `housing.csv`, `iris.csv`) estejam no mesmo diretório do notebook ou atualize os caminhos no código conforme necessário.

5. **Execute o notebook**
   Inicie o Jupyter Notebook e abra o arquivo `main.ipynb`:

   ```bash
   jupyter notebook main.ipynb
   ```

6. **Execute as células**
   No Jupyter Notebook, execute cada célula em sequência. O código carregará os dados, treinará os modelos e exibirá os resultados.
