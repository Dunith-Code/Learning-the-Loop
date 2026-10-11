<div align="center">

# 🔁 Learning the Loop

### Machine learning explained with **real data** and **reproducible numbers**, from fundamentals to a real reinforcement learning system.

[![Medium](https://img.shields.io/badge/Read%20on-Medium-black?logo=medium)](https://medium.com/@Dunith-Write)
[![LinkedIn](https://img.shields.io/badge/Follow-LinkedIn-0A66C2?logo=linkedin)](https://linkedin.com/in/dunith/)
![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Series-In%20progress-orange)

</div>

---

## 📖 About

**Learning the Loop** is an article series where I document what I'm learning about AI/ML while building a real **reinforcement learning system** for my final-year thesis (adaptive traffic signal control).

The idea behind the name: almost every ML algorithm runs the same loop, **predict → measure error → adjust → repeat**. This series unpacks that loop one concept at a time.

From #103 onward, every number, figure and table in the articles is produced by the companion notebook in this repository, so you can run it and check it yourself.

---

## 🗂️ Articles & notebooks

| # | Article | Topic | Notebook |
|---|---------|-------|----------|
| 101 | [What Is Machine Learning, Really?](https://medium.com/@Dunith-Write/learning-the-loop-101-what-is-machine-learning-really-aac03c3e1268) | The core idea of ML | — |
| 102 | [The Types of Machine Learning](https://medium.com/@Dunith-Write/learning-the-loop-102-the-types-of-machine-learning-and-why-the-distinction-actually-matters-cfd7a61a22d8) | Supervised, unsupervised, reinforcement | — |
| 103 | [How Does a Model Actually Learn?](https://medium.com/@Dunith-Write/learning-the-loop-103-how-does-a-model-actually-learn-loss-functions-gradient-descent-0e3612e3b761) | Loss functions & gradient descent | [`learning_the_loop_103_practical.ipynb`](./learning_the_loop_103_practical.ipynb) |
| 104 | [Overfitting vs. Underfitting](https://medium.com/@Dunith-Write/learning-the-loop-104-overfitting-vs-underfitting-why-memorizing-isnt-learning-8a6d6038020c?sharedUserId=Dunith-Write) | Why memorizing isn't learning | [`learning_the_loop_104_practical.ipynb`](./learning_the_loop_104_practical.ipynb) |

> 🔜 **Coming next:** #105 K-Nearest Neighbors on the Iris dataset.

---

## 🧭 Series roadmap

- **🧱 Phase 1: Fundamentals** (#101–#105): ML basics, loss & gradient descent, overfitting, KNN
- **🌳 Phase 2: Classical ML**: decision trees, ensembles, evaluation metrics
- **🧠 Phase 3: Neural networks**: forward pass, backpropagation, CNNs, RNNs/LSTMs
- **🎮 Phase 4: Reinforcement learning**: Q-learning, DQN, Double DQN, prioritized replay
- **🚦 Phase 5: Thesis showcase**: dueling networks & attention, CNN-LSTM, multi-agent traffic signal control, simulation to real-time deployment

*The plan may change as the series evolves.*

---

## 📁 Repository structure

```
Learning-the-Loop/
├── learning_the_loop_103_practical.ipynb   # Loss functions & gradient descent
├── learning_the_loop_104_practical.ipynb   # Overfitting vs. underfitting
└── README.md
```

Each notebook is self-contained: it loads its own data, runs the experiments, and draws the figures.

---

## 🚀 Getting started

### ☁️ Option 1: Google Colab (no setup)
Open a notebook from this repository on GitHub, then click **Open in Colab**. Or paste the notebook's GitHub URL into [colab.research.google.com](https://colab.research.google.com) (File → Open notebook → GitHub tab). Then run all cells from top to bottom.

### 💻 Option 2: Run locally

**1️⃣ Clone the repository**
```bash
git clone https://github.com/Dunith-Code/Learning-the-Loop.git
cd Learning-the-Loop
```

**2️⃣ Create a virtual environment (recommended)**
```bash
python -m venv .venv

# Windows (PowerShell)
.venv\Scripts\Activate.ps1

# macOS / Linux
source .venv/bin/activate
```

**3️⃣ Install dependencies**
```bash
python -m pip install numpy matplotlib scikit-learn jupyter
```

**4️⃣ Launch Jupyter and open a notebook**
```bash
jupyter notebook
```
Run the cells top to bottom. #104 repeats its experiments over 200 random splits, so that notebook takes a little longer to finish.

---

## 🔬 Reproducibility

- 📊 **Real datasets**, loaded from `scikit-learn` (the diabetes dataset in #103 and #104)
- 🎲 **Fixed seeds**: the only randomness is the train/test split seeds, so reruns give the same numbers
- 🧮 **Medians over many splits** where a single split could mislead (#104 uses 200)
- 🚫 **If your numbers differ from the article's:** that's a real bug worth reporting.

---

## 🧰 Tech stack

`Python` · `NumPy` · `scikit-learn` · `Matplotlib` · `Jupyter`
*(Later phases will add PyTorch, SUMO and OpenCV/YOLO.)*

---

## 🤝 Feedback & contributions

Found a bug, a typo, or a number that doesn't reproduce? 🐛
Please [open an issue](../../issues), and suggestions for future topics are welcome too. 💡

---

## 📚 References

- Efron, B., Hastie, T., Johnstone, I., & Tibshirani, R. (2004). *Least Angle Regression*. Annals of Statistics, 32(2).
- Pedregosa, F., et al. (2011). *Scikit-learn: Machine Learning in Python*. JMLR, 12.
- Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press.
- Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction* (2nd ed.). MIT Press.

---

## 👤 Author

**Dunith Desitha Athukorala**
<br/>
Final-year Instrumentation & Automation Technology undergraduate, University of Colombo 🇱🇰
<br/>
Information Technology undergraduate, University of Colombo School of Computing 🇱🇰
<br/>

**✍️ [Medium](https://medium.com/@Dunith-Write) · 💼 [LinkedIn](https://linkedin.com/in/dunith) · 🌐 [Portfolio](https://dunith-code.github.io)**

---

<div align="center">

**Learn 📘 | Loop 🔁 | Level Up 🚀**

⭐ If this series helps you, consider starring the repo!

</div>