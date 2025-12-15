# 🧠 Deep Learning Journey & Portfolio

![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?logo=keras)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?logo=jupyter)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)

---

## 📌 Project Overview
Acest repository documentează progresul meu în **Deep Learning** și **Computer Vision**, de la manipularea tensorilor până la construirea și antrenarea rețelelor neuronale convoluționale (CNN) complexe.

Proiectul urmărește o curbă de învățare structurată, trecând prin:
- **Fundamente**: Regresie, Clasificare, Tensori.
- **Computer Vision**: Clasificare Binară și Multi-clasă pe imagini reale.
- **Optimizare**: Data Augmentation, prevenirea Overfitting-ului și tunarea hiperparametrilor.

---

## 🛠️ Technical Stack

| Tehnologie | Scop | Caracteristici Cheie |
|------------|------|----------------------|
| **TensorFlow & Keras** | Deep Learning Core | Construirea rețelelor (Sequential API), straturi (Conv2D, Dense) |
| **Python 3** | Limbaj Principal | Scripting, OOP, Data Manipulation |
| **Matplotlib** | Vizualizare | Grafice pentru Loss & Accuracy curves, vizualizare imagini |
| **NumPy** | Procesare Numerică | Manipulare array-uri și tensori |
| **ImageDataGenerator** | Pre-procesare | Augmentarea datelor, normalizare (rescaling), batching |

---

## 📊 Key Features & Projects

### 🔹 Computer Vision (CNNs)
Focusul principal al repository-ului. Include implementări de la zero ale arhitecturii **TinyVGG**.

- **Pizza 🍕 vs. Steak 🥩 (Binary Classification)**:
    - Model CNN antrenat să distingă între două clase de mâncare.
    - Utilizare `binary_crossentropy` și activare `sigmoid`.
    - Acuratețe de bază vs. modele optimizate.
- **Food101 - 10 Clase (Multi-class Classification)**:
    - Extinderea modelului pentru a recunoaște 10 tipuri diferite de mâncare (Sushi, Burger, etc.).
    - Utilizare `categorical_crossentropy` și activare `softmax`.
- **Lupta cu Overfitting**:
    - Implementare **Data Augmentation** (rotire, zoom, flip) pentru a generaliza mai bine.
    - Simplificare arhitectură și MaxPooling.

### 🔹 Deep Learning Fundamentals
- **Tensors**: Manipulare, operații matriceale, GPU acceleration.
- **Regression**: Prezicerea valorilor continue.
- **Classification**: Clasificarea punctelor de date (ex: cercuri, spirale).

### 🔹 Planned Modules (In Progress)
Structura este pregătită pentru viitoarele proiecte care sunt în lucru:
- 📂 **Transfer Learning**: Folosirea modelelor pre-antrenate (ex: ResNet, EfficientNet).
- 📂 **NLP (Natural Language Processing)**: Procesarea textului.
- 📂 **Time Series**: Predicții pe serii temporale.

---

## 📂 Repository Structure

```text
Deep-Learning-Journey/
│
├── 📁 Computer_Vision/       # CNN-uri, Pizza vs Steak, Food101
│   ├── CNN.ipynb
│   ├── CNN_classification.ipynb
│   └── ...
│
├── 📁 Fundamentals/          # Bazele TensorFlow (Regresie, Clasificare)
│   ├── Manipulating_tensors.ipynb
│   └── ...
│
├── 📁 Projects/              # Proiecte aplicate (Clothing, Medical)
├── 📁 Transfer_Learning/     # (Coming Soon)
├── 📁 Natural_Language_Procesing/
│
├── 📜 requirements.txt       # Dependințe
└── 📝 README.md              # Documentație
```
Problema este că în previzualizarea ta, textul nu are spații suficiente între rânduri și lipsesc marcajele pentru cod (acele accente grave \`\`\`). Markdown este sensibil la spațiere: dacă nu lași un rând liber între titlu și text, sau între text și cod, totul apare pe o singură linie.

Iată partea de final (de la structura folderelor în jos) **formatată corect**.

Copiază codul de mai jos și înlocuiește tot ce ai în fișierul tău, începând de la linia cu `## 📂 Repository Structure`:

````markdown
## 📂 Repository Structure

```text
Deep-Learning-Journey/
│
├── 📁 Computer_Vision/       # CNN-uri, Pizza vs Steak, Food101
│   ├── CNN.ipynb
│   ├── CNN_classification.ipynb
│   └── ...
│
├── 📁 Fundamentals/          # Bazele TensorFlow (Regresie, Clasificare)
│   ├── Manipulating_tensors.ipynb
│   └── ...
│
├── 📁 Projects/              # Proiecte aplicate (Clothing, Medical)
├── 📁 Transfer_Learning/     # (Coming Soon)
├── 📁 Natural_Language_Procesing/
│
├── 📜 requirements.txt       # Dependințe
└── 📝 README.md              # Documentație
````

-----

## 🚀 Getting Started

### ✅ Prerequisites

  * Python 3.7+
  * Jupyter Notebook / Google Colab
  * **Biblioteci:** TensorFlow, Matplotlib, Numpy, Pandas

### 🔧 Installation

1.  **Clonează repository-ul:**

    ```bash
    git clone [https://github.com/Darius-Cos/Deep-Learning-Journey.git](https://github.com/Darius-Cos/Deep-Learning-Journey.git)
    cd Deep-Learning-Journey
    ```

2.  **Instalează dependențele:**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Descarcă Datele:**

    > **Notă:** Seturile de date (imaginile `pizza_steak`, etc.) **NU** sunt incluse în repo pentru a economisi spațiu și bandă.
    > Rulează prima celulă din notebook-urile `Computer_Vision` pentru a descărca automat datele de pe serverele de stocare.

-----


⭐ **Dacă îți place acest proiect, dă-i un Star pe GitHub\!**

```
```
