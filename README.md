# Data Face Recognition

A simple and efficient face registration and recognition API built with FastAPI, SQLite (via Prisma), and face embedding extraction using a face recognition model.

---

## 🧠 Features

- **Register employees and visitors**  
  Upload an image + metadata (name, age, gender) to store face embeddings.
- **Recognize faces**  
  Upload a photo to identify registered persons based on cosine similarity.
- **Lightweight and modular**  
  Uses FastAPI, Prisma ORM, SQLite, and an embedder of your choice.

---

## 📦 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/saranjthilak/data-face-recognition.git
   cd data-face-recognition




## Face Recognition with PCA

We'll apply PCA to reduce the size of black & white images before applying classification algorithms:
- Start with `warmup_pca.ipynb` if you want to warm up on PCA
- Then, move on to `face_recognition.ipynb` for the main course!


<img src="https://scikit-learn.org/stable/_images/sphx_glr_plot_face_recognition_001.png" width=500>
