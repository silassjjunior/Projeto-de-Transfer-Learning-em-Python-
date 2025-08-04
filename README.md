# 🧠 Detecção e Classificação de Gatos e Cachorros com YOLOv8 + MobileNetV2

Este projeto combina **detecção de objetos** com **transfer learning**, usando **YOLOv8** para localizar animais em imagens e **MobileNetV2** treinado com pesos do **ImageNet** para classificá-los com mais precisão.

---

## 📌 Descrição Rápida

Aplicamos **YOLOv8** para detectar regiões contendo gatos ou cachorros recortá-las e classifica-las com um % de precisão. 
Em seguida, utilizamos **MobileNetV2**, uma rede pré-treinada com pesos do **ImageNet**, para realizar a classificação com maior acurácia. Essa abordagem simula sistemas reais de visão computacional.
Reajustamos a Ultima camada para detectar apenas Gatos e Cachorros.
Fizemos um Treinamento com o Dataset Cats and Dogs do TensorFlow
plotamos a curva de aprendizado e o novo resultado.
Depois fizemos mais uma rodada de aprendizados e plotamos os resultados.

Utilizando dessa logica para entender o Fluxo de Machine Learning e Transfer Learning 

---

## 🔧 Tecnologias Utilizadas

- `Python`
- `Google Colab`
- `TensorFlow / Keras`
- `PyTorch`
- `YOLOv8`
- `MobileNetV2`
- `ImagiNet`
- `Matplotlib`, `NumPy`

## 🚀 Como Executar

1. Acesse o notebook no Google Colab:  
   👉 [Abrir no Colab] (https://colab.research.google.com/drive/1ostZPCecC8HBjmtLP5GwWfsaZCp_ZC2_?usp=sharing)

2. Siga os passos dentro do notebook:

   Clique em Executar Tudo
   
   Adicione uma Imagem (Modelo de Teste Disponivel)
   
   Aguarde os Resultados.

---

## 📊 Resultados

- O modelo atinge boa acurácia com apenas algumas épocas.
- A combinação de detecção + classificação melhora a robustez.
- Visualizações com imagens detectadas e classificadas.
- Observação de Melhora no reconhecimento

---

## 💡 Diferenciais do Projeto

- Integra duas abordagens poderosas (YOLO + Transfer Learning).
- Reduz ruído nas imagens ao focar apenas nos objetos detectados.
- Arquitetura moderna e leve (MobileNetV2).
- Código comentado e visualizações incluídas.

---

## 📚 Base de Dados

- Dataset utilizado: [`cats_vs_dogs`](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs)

---

## 👨‍💻 Autor

**Silas Junior**  
Projeto desenvolvido como parte da formação em IA e Deep Learning pela [Digital Innovation One (DIO)](https://www.dio.me)

---

## 🧠 Conceitos Trabalhados

- Transfer Learning
- Detecção de Objetos
- Fine-Tuning de modelos pré-treinados
- Classificação binária
- Visualização e avaliação de desempenho
---


