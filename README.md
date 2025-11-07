# 🧠 Transfer Learning com Deep Learning - Classificação de Imagens

## 🎯 Objetivo
Este projeto tem como objetivo aplicar o método de **Transfer Learning** utilizando um modelo pré-treinado para realizar a **classificação de imagens** entre duas classes: **gatos** e **cachorros**. O desenvolvimento foi realizado em **Python** no ambiente **Google Colab**.

---

## 📁 Dataset Utilizado
Utilizamos o dataset **Cats vs Dogs**, disponível no Kaggle:

🔗 [Cats vs Dogs - Kaggle](https://www.kaggle.com/datasets/sreetejadusi/cats-vs-dogs)

**Descrição:**
- Contém milhares de imagens de gatos e cachorros.
- As imagens estão organizadas em pastas para treino e validação.
- Ideal para tarefas de classificação binária.

---

## ⚙️ Metodologia

### 1. Pré-processamento
- Redimensionamento das imagens para tamanho padrão (224x224).
- Normalização dos pixels.
- Separação em conjuntos de treino e validação.

### 2. Modelo Utilizado
- Modelo pré-treinado: `VGG16` (ou `ResNet50`, `MobileNetV2`, etc).
- Remoção da camada de saída original.
- Adição de camadas densas para classificação binária.

### 3. Treinamento
- Congelamento das camadas convolucionais iniciais.
- Fine-tuning das camadas finais.
- Otimizador: Adam
- Função de perda: Binary Crossentropy
- Métrica: Acurácia

---

## 📊 Resultados Esperados
- Acurácia superior a 90% na validação.
- Redução significativa da perda durante o treinamento.
- Classificação eficiente entre gatos e cachorros.

---

## 🚀 Execução no Google Colab

### Passos:
1. Acesse o notebook `transfer_learning_cats_vs_dogs.ipynb` no Colab.
2. Faça upload do dataset ou conecte com o Kaggle.
3. Execute as células passo a passo.
4. Visualize os gráficos de desempenho e os resultados.

---

## 📝 Observações
- Você pode substituir o dataset por imagens pessoais ou outras classes.
- O projeto pode ser expandido para múltiplas classes com ajustes no modelo.

---

## 📷 Imagens
Capturas de tela do treinamento e resultados estão disponíveis na pasta `/images`.

---

## 📌 Autor
Projeto desenvolvido como parte do desafio da **DIO - Digital Innovation One**.
