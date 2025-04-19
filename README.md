# Neural Style Transfer Art 🎨

This project implements **Neural Style Transfer (NST)** — a fascinating technique that combines the **content of one image** with the **style of another**, producing a new image that looks like a painting of the original photo. This project is inspired by DeepLearning.AI's Deep Learning Specialization (Course 4: Convolutional Neural Networks), showcasing the creative power of convolutional layers beyond classification tasks.

## 🖼️ What Is Neural Style Transfer?

NST works by blending:

- **Content Image (C)**: The image whose layout and structure you want to preserve.
- **Style Image (S)**: The image whose visual style (colors, brush strokes, textures) you want to apply.
- **Generated Image (G)**: The output that merges the content from **C** and style from **S**.

This is achieved by optimizing a loss function that combines:
- **Content Loss**: How different G is from C.
- **Style Loss**: How different G is from S.
- **Total Loss** = α * Content Loss + β * Style Loss
