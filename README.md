# Applied Data Analysis Tasks Repository

Welcome to my Applied Data Analysis repository! 📊  
This repo contains a collection of completed applied data analysis exercises and experiments, implemented in Jupyter Notebooks (.ipynb).  

All tasks were completed as part of the *Applied Data Analysis course (minor: Intellectual Data Analysis)* at HSE.  
Each notebook is self-contained; imports are provided inline, and main libraries are also listed in requirements.txt.  

---

## 📂 Repository Structure  

├── ADA1_GAN.ipynb  
├── ADA2_audio.ipynb  
├── ADA3_YOLO.ipynb  
├── ADA4_recSys.ipynb  
├── requirements.txt  
├── LICENSE <br />
└── README.md  

---

## 📑 Task Overview  

| Notebook | Topic | Key Concepts | Notes |
|----------|-------|--------------|-------|
| ADA1_GAN.ipynb | ✨ GAN & Diffusion Models for Particle Images | Generative Adversarial Networks, Diffusion models | Generated synthetic images of gamma photons vs. hadrons to help astronomers classify expensive-to-obtain particle images, saving resources through generative modeling. |
| ADA2_audio.ipynb | 🎵 Audio Data Analysis | Mel-spectrograms, RNNs, CNNs, SpecAugment | Explored audio data formats, implemented audio classifiers using recurrent and convolutional architectures, and applied SpecAugment for data augmentation. |
| ADA3_YOLO.ipynb | 🧙 Object Detection on Harry Potter Dataset | YOLO architecture, object detection, custom implementation | Built YOLO object detection model nearly from scratch, implementing all major functions, and compared with pre-built solutions. |
| ADA4_recSys.ipynb | 🎶 Music Recommendation System | Collaborative filtering, Pearson correlation, Jaccard similarity, Latent Factor Models | Designed recommender systems for music tracks. Implemented MAP@k metric, User2User collaborative filtering, similarity measures, and latent factor models for track prediction. |

---

## ⚙️ Setup & Installation  

To run the notebooks locally, you’ll need Python 3.8+ and the dependencies listed in requirements.txt.  

```bash
git clone https://github.com/yourusername/applied-data-analysis-tasks.git
cd applied-data-analysis-tasks
pip install -r requirements.txt
```

Or, open directly in Google Colab.  

---

## 🧑‍💻 Usage  

1. Launch Jupyter Notebook or Jupyter Lab:  

```bash
jupyter notebook
```

2. Open the notebook of interest (e.g., `ADA1_GAN.ipynb`).  
3. Run cells step by step to explore code, results, and commentary.  

---

## 📊 Results & Visualizations  

Each notebook includes:  
 • Explanations of the approach  
 • Evaluation metrics (accuracy, precision/recall, MAP@k, etc.)  
 • Key visualizations (plots, generated images, spectrograms, detection outputs)  
 • Reflections on results and limitations  

---

## 🛠 Dependencies  

Main libraries used across notebooks:  
 • [PyTorch](https://pytorch.org/)  
 • NumPy, Pandas  
 • Matplotlib, Seaborn  
 • scikit-learn  

See requirements.txt for the full list.  

---

## 🌟 Future Work  

Planned extensions:  
 • Experiments with diffusion models in more applied tasks  
 • Advanced audio feature extraction (MFCCs, transformers for audio)  
 • Larger recommender systems with hybrid models  
 • Applied object detection on new datasets  

---

## 📜 License  

This repository is released under the MIT License.  
Feel free to fork, explore, and build upon it!  

---

## 👤 Author  

Created by [Anastasiia Lapshina](https://github.com/lapshinaaa).  
Feel free to reach out via GitHub Issues if you’d like to collaborate or discuss ideas.  
