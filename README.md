Projeto de Machine Learning: Classificação de Dígitos com o Dataset MNIST

Este projeto segue o passo a passo do livro Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras & TensorFlow e tem como objetivo aplicar técnicas de aprendizado de máquina supervisionado para classificação de dígitos escritos à mão utilizando o dataset MNIST.

📌 Sobre o Projeto

O MNIST (
Modified National Institute of Standards and Technology) é um dos datasets mais famosos em Machine Learning, contendo imagens de dígitos de 0 a 9, com dimensão 28x28 pixels em escala de cinza.
O objetivo é treinar modelos de aprendizado de máquina para reconhecer e classificar corretamente os dígitos.

🛠 Tecnologias Utilizadas

Linguagem: Python

Bibliotecas:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-Learn


🔧 Instalação e Configuração

Clone este repositório:

git clone https://github.com/CarlosFranchN/ML_Mnist_Geron_aplication.git

Acesse o diretório do projeto:

Crie um ambiente virtual (opcional, mas recomendado):

python -m venv venv
source venv/bin/activate  # Para Linux/Mac
venv\Scripts\activate     # Para Windows

Instale as dependências:

pip install -r requirements.txt

📊 Passos do Projeto

Carregamento e Exploração dos Dados

Download do dataset MNIST

Visualização de amostras

Análise estatística dos dados

Pré-processamento

Normalização dos pixels

Divisão entre treino e teste

Transformar imagens para entrada em modelos

Treinamento de Modelos

Avaliação dos Modelos

Matrizes de confusão

Métricas: Precisão, Revocação, F1-score

Curvas ROC e AUC

Validação e Otimização

Ajuste de hiperparâmetros

Redução de overfitting

📌 Como Executar o Projeto

Execute o Jupyter Notebook:

jupyter notebook

Abra o arquivo principal.

Siga os passos no notebook para carregar e treinar os modelos.

🔍 Resultados

Os modelos treinados serão avaliados com base em métricas como acurácia, matriz de confusão e curvas ROC. A meta é obter um desempenho de classificação próximo ao estado da arte para este dataset.

📌 Referências

Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras & TensorFlow - Aurélien Géron

Documentação oficial do Scikit-Learn

📜 Licença

Este projeto é de uso livre para estudo e aprendizado. Sinta-se à vontade para contribuir! 😊
