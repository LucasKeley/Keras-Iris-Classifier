# Keras-Iris-Classifier

# Keras: Primeiros Passos com Redes Neurais e o Iris Dataset

<p align="center">
  <img src="https://www.embedded-robotics.com/wp-content/uploads/2022/01/Iris-Dataset-Classification.png" alt="Iris Dataset Classification" width="500"/>
</p>

Este projeto explora os primeiros passos na construção e treinamento de redes neurais utilizando a **biblioteca Keras** com o famoso **Iris Dataset**. O Iris Dataset é um conjunto de dados acadêmico que contém 150 amostras de três espécies de flores Iris (*Iris setosa, Iris virginica e Iris versicolor*), cada uma com quatro características medidas: comprimento e largura das sépalas e pétalas. O objetivo é classificar as espécies de flores com base nessas características.

O projeto demonstra conceitos fundamentais de redes neurais, desde a criação de um Perceptron simples até a construção e avaliação de um Multi-Layer Perceptron (MLP) para classificação.

---

## 🎯 Objetivo do Projeto

* **Compreender** o funcionamento básico de um Perceptron e um MLP.
* **Construir** modelos de redes neurais com a biblioteca Keras.
* **Preparar e normalizar** dados para treinamento de modelos de Machine Learning.
* **Treinar e avaliar** o desempenho de modelos de classificação.
* **Visualizar** o processo de aprendizado do modelo.

---

## 💻 Tecnologias Utilizadas

* **Python**
* **TensorFlow/Keras**: Para a construção e treinamento das redes neurais.
* **Scikit-learn**: Para manipulação de dados, como o carregamento do Iris Dataset, normalização e divisão em conjuntos de treino e teste.
* **Matplotlib** e **Seaborn**: Para visualização e análise de dados.

---

## ✨ Principais Funcionalidades

* **Criação de Perceptron:** Demonstração da estrutura de um Perceptron, seus pesos e vieses.
* **Visualização de Dados:** Análise exploratória do Iris Dataset com gráficos de dispersão das sépalas e pétalas.
* **Pré-processamento de Dados:**
    * Categorização das classes (labels).
    * Normalização das características utilizando `MinMaxScaler`.
    * Divisão dos dados em conjuntos de treino e teste (80/20) com `stratify`.
* **Construção de MLP:** Criação de um modelo MLP com camada de entrada, camada oculta (512 neurônios com ativação ReLU) e camada de saída (3 neurônios com ativação Softmax para classificação).
* **Treinamento do Modelo:** Compilação com `categorical_crossentropy` e `rmsprop` e treinamento por 100 épocas.
* **Avaliação do Modelo:**
    * Análise das curvas de perda e acurácia de treino e validação.
    * Avaliação final no conjunto de teste.
    * Exemplo de predição com novas entradas.

---

## 🚀 Como Rodar o Projeto Localmente

Siga os passos abaixo para configurar e executar o projeto em sua máquina:

1.  **Clone o repositório:**

    ```bash
    git clone [https://github.com/LucasKeley/Keras-Iris-Classifier.git](https://github.com/LucasKeley/Keras-Iris-Classifier.git)
    cd Keras-primeiros-passos
    ```

2.  **Crie e ative um ambiente virtual (recomendado):**

    ```bash
    python -m venv venv
    # No Windows
    .\venv\Scripts\activate
    # No macOS/Linux
    source venv/bin/activate
    ```

3.  **Instale as dependências:**

    ```bash
    pip install tensorflow scikit-learn matplotlib seaborn
    ```

4.  **Execute o notebook Jupyter:**

    ```bash
    jupyter notebook Notebook_Keras_primeiros_passos.ipynb
    ```

    Isso abrirá o Jupyter Notebook em seu navegador, onde você poderá executar as células e interagir com o código.

---

## 🤝 Como Contribuir

Sua contribuição é muito bem-vinda! Se você encontrar algum bug, tiver sugestões de melhoria ou quiser adicionar novas funcionalidades, siga estas etapas:

1.  Faça um `fork` deste repositório.
2.  Crie uma nova `branch` para sua feature ou correção de bug: `git checkout -b feature/sua-feature-nova` ou `fix/corrige-bug`.
3.  Faça suas alterações e commit-as: `git commit -m 'feat: Adiciona nova funcionalidade'` ou `fix: Corrige erro X`.
4.  Envie suas alterações para o seu fork: `git push origin feature/sua-feature-nova`.
5.  Abra um `Pull Request` detalhando suas mudanças.

---

## 📄 Licença

Este projeto está licenciado sob a licença [MIT](LICENSE).

---

## ❤️ Agradecimentos

Agradeço à comunidade de código aberto e aos criadores das bibliotecas utilizadas por tornarem a inteligência artificial mais acessível e empolgante!

Agradeço á Instrutora Mirla Costa: Linkedin(https://www.linkedin.com/in/mirla-costa/)

Agredeço à Alura
