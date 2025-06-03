# Facial Alignment via Landmark-Guided Morphing with Cosine Similarity Analysis  
**Alinhamento Facial via Morphing Guiado por Landmarks com Análise de Similaridade do Cosseno**

## 📌 Sobre o Projeto | About the Project

Este projeto foi desenvolvido como parte da disciplina de Processamento Digital de Imagens no curso de Engenharia da Computação da Escola Politécnica de Pernambuco (UPE). O objetivo principal é aplicar técnicas de alinhamento facial (Face Alignment) utilizando morfing facial baseado em landmarks, com posterior avaliação via similaridade de cosseno.

This project was developed as part of the Digital Image Processing course in the Computer Engineering program at Escola Politécnica de Pernambuco (UPE). The main goal is to apply Face Alignment techniques using landmark-based face morphing, followed by cosine similarity evaluation.

---

## ⚙️ Tecnologias e Bibliotecas | Technologies and Libraries

- Python (Google Colab)
- OpenCV → Processamento de imagens
- dlib → Extração dos 68 landmarks faciais
- NumPy → Manipulação de arrays
- Matplotlib / Pillow → Visualização de imagens
- scikit-learn → Cálculo da similaridade de cosseno

---

## 🔍 Etapas do Projeto | Project Steps

1. **Extração de Landmarks**: Uso do modelo `dlib` para obter 68 pontos da face.
2. **Face Morphing**: Transformações geométricas entre imagens desalinhadas e uma imagem base.
3. **Pré-processamento**: Normalização, corte e ajuste de cor.
4. **Avaliação**: Cálculo da similaridade de cosseno entre imagens alinhadas e a imagem de referência.
5. **Análise de Regiões**: Verificação do impacto de diferentes regiões (olhos, boca, etc.) no reconhecimento facial.

---

## 📊 Resultados | Results

- A substituição da região dos **olhos** foi a que mais aumentou a similaridade de cosseno.
- Combinações de múltiplas regiões nem sempre melhoraram os resultados.
- O alinhamento sem ML mostrou-se possível e instrutivo para entender o impacto anatômico das regiões faciais.

---

## 📁 Dataset

Utilizou-se um subconjunto manualmente montado com pares de imagens (frontal e perfil) de 50 celebridades, devido a limitações na qualidade das imagens do dataset LFW em tempo de execução.

---

## 📸 Exemplos Visuais | Visual Examples

(Imagens e gráficos de antes/depois, landmarks e resultados de similaridade podem ser incluídos aqui no repositório.)

---

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
