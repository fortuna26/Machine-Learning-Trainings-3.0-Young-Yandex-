**Home Work 6 Task B. Operation: EchoTrace fixed - Image Similarity Search**

In this task we built a system to detect AI-generated imitations by finding the most similar images in a [dataset](https://disk.yandex.ru/d/Hu-um0ASI6eAUg). 
Each image serves as both a query and a candidate for recommendation.

**Goal:** For each image, identify the 6 most similar images (excluding itself).

**Approach:**  
- Used `timm` library with a **DINO model** (self-supervised Vision Transformer) for feature extraction  
- Computed image embeddings and measured similarity  
- Achieved required accuracy (≥0.5 match rate) and submitted results to Contest system
