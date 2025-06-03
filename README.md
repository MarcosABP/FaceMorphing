# Facial Alignment via Landmark-Guided Morphing with Cosine Similarity Analysis  
**Alinhamento Facial via Morphing Guiado por Landmarks com Análise de Similaridade do Cosseno**

## 📌 Sobre o Projeto | About the Project

Este projeto foi desenvolvido como parte da disciplina de Processamento Digital de Imagens no curso de Engenharia da Computação da Escola Politécnica de Pernambuco (UPE). O objetivo principal é aplicar técnicas de alinhamento facial (Face Alignment) utilizando morfing facial baseado em landmarks, com posterior avaliação via similaridade de cosseno.

This project was developed as part of the Digital Image Processing course in the Computer Engineering program at Escola Politécnica de Pernambuco (UPE). The main goal is to apply Face Alignment techniques using landmark-based face morphing, followed by cosine similarity evaluation.

---

## ⚙️ Tecnologias e Bibliotecas | Technologies and Libraries

- Python (Google Colab)
- OpenCV → Processamento de imagens / Image Procesing
- dlib → Extração dos 68 landmarks faciais / Extraction of 68 facial landmarks
- NumPy → Manipulação de arrays / Array Manipulation
- Matplotlib / Pillow → Visualização de imagens / Image Visualisation
- scikit-learn → Cálculo da similaridade de cosseno / Cosine similarity evaluation

---

## 🔍 Etapas do Projeto | Project Steps

1. **Extração de Landmarks**: Uso do modelo `dlib` para obter 68 pontos da face.  
   **Landmark Extraction**: Using the `dlib` model to obtain 68 facial points.

2. **Face Morphing**: Transformações geométricas entre imagens desalinhadas e uma imagem base.  
   **Face Morphing**: Geometric transformations between misaligned images and a base image.

3. **Pré-processamento**: Normalização, corte e ajuste de cor.  
   **Preprocessing**: Normalization, cropping, and color adjustment.

4. **Avaliação**: Cálculo da similaridade de cosseno entre imagens alinhadas e a imagem de referência.  
   **Evaluation**: Calculation of cosine similarity between aligned images and the reference image.

5. **Análise de Regiões**: Verificação do impacto de diferentes regiões (olhos, boca, etc.) no reconhecimento facial.  
   **Region Analysis**: Assessing the impact of different facial regions (eyes, mouth, etc.) on face recognition.

---

## 📊 Resultados | Results

- A substituição da região dos **olhos** foi a que mais aumentou a similaridade de cosseno.  
  The substitution of the **eye** region showed the greatest increase in cosine similarity.

- Combinações de múltiplas regiões nem sempre melhoraram os resultados.  
  Combinations of multiple regions did not always improve results.

- O alinhamento sem ML mostrou-se possível e instrutivo para entender o impacto anatômico das regiões faciais.  
  Alignment without ML proved feasible and instructive to understand the anatomical impact of facial regions.

---

## 📁 Dataset

Utilizou-se um subconjunto manualmente montado com pares de imagens (frontal e perfil) de 50 celebridades, devido a limitações na qualidade das imagens do dataset LFW em tempo de execução.  
A manually curated subset with pairs of images (frontal and profile) from 50 celebrities was used, due to runtime quality limitations of the LFW dataset images.


## 👨‍💻 Autores | Authors

- Gabriel Albuquerque  
- Mário Guerra  
- Marcos Prudêncio

---

## 📚 Referências | References

- Thakur, A. (2021). *Face morphing using OpenCV*.  
- Wang, A. (2021). *Face morphing: A step-by-step tutorial*.  
- GeeksForGeeks. *Face Alignment with OpenCV and Python*.  
- Kähäri, M. (2020). *Facial landmarks and face alignment with Dlib*.  

---

## 📅 Ano | Year

2025 — Escola Politécnica de Pernambuco – Universidade de Pernambuco (UPE)
