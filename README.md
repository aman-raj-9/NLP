# NLP Projects

A collection of Natural Language Processing (NLP) projects and practice notebooks covering fundamental NLP concepts, text processing techniques, and machine learning applications.

This repository is created to learn, implement, and explore NLP concepts through practical examples using Python.

## 📚 Topics Covered

### 1. NLP Fundamentals
- **Text Preprocessing:** Text cleaning, tokenization, stopword removal, stemming, and lemmatization.
- **Text Representation:** One-Hot Encoding, Bag of Words (BoW), N-Grams, and TF-IDF.
- **Word2Vec:** Understanding CBOW and Skip-Gram word embedding techniques.
- **POS Tagging:** Identifying parts of speech in text.
- **Text Classification:** Applying machine learning techniques to classify text.

### 2. Question Similarity Analysis
A machine learning project that analyzes whether two questions have similar meanings.

**Key concepts:**
- Text preprocessing and cleaning
- TF-IDF vectorization
- Cosine similarity
- Feature engineering
- Common word ratio and text length features
- Model training and comparison

**Machine learning models explored:**
- Logistic Regression
- Random Forest Classifier
- Support Vector Classifier (SVC)

The project demonstrates how NLP techniques and machine learning can be combined to identify similar questions.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- NLTK
- Gensim
- Beautiful Soup
- Jupyter Notebook

## 📁 Repository Structure

```text
NLP Projects/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── NLP Fundamentals/
│   ├── Text Preprocessing.ipynb
│   ├── Text Representation.ipynb
│   ├── Word2Vec.ipynb
│   ├── POS Tagging.ipynb
│   ├── Text Classification.ipynb
│   └── Saved Model/
│
└── Question Similarity Analysis/
    └── question_similarity_analysis.ipynb
```

*Note: The structure above is illustrative. Actual filenames and folders may differ slightly.*

## 🚀 Getting Started

Follow these steps to run the notebooks on your local machine.

### Step 1: Clone the Repository

Open your terminal or command prompt and run:

```bash
git clone https://github.com/aman-raj-9/NLP.git
```

### Step 2: Open the Project Folder

```bash
cd NLP
```

### Step 3: Create a Virtual Environment (Recommended)

```bash
python -m venv .venv
```

Activate the environment.

**Windows:**

```bash
.venv\Scripts\activate
```

**macOS / Linux:**

```bash
source .venv/bin/activate
```

### Step 4: Install Required Libraries

Make sure `requirements.txt` is present in the project root directory. Run:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

This installs the Python libraries listed in `requirements.txt`.

### Step 5: Launch Jupyter Notebook

```bash
jupyter notebook
```

Alternatively, you can use JupyterLab or open the project in VS Code with the Jupyter extension installed.

### Step 6: Open and Run a Notebook

Navigate to either the `NLP Fundamentals` or `Question Similarity Analysis` folder, open the notebook you want to explore, and run the cells in order.

**Important:** If a notebook requires a dataset or an additional NLTK resource, make sure that resource is available before running the notebook. Run the notebook's setup cells first when provided.

## 📦 Requirements

The dependencies for this repository are listed in `requirements.txt`.

Install them using:

```bash
pip install -r requirements.txt
```

If a notebook uses an additional library that is not listed in `requirements.txt`, install that library separately and consider adding it to the requirements file.

## 🎯 Learning Objectives

- Understand the fundamentals of Natural Language Processing.
- Learn different text preprocessing and text representation techniques.
- Explore word embeddings and POS tagging.
- Apply machine learning algorithms to text classification.
- Build a question similarity analysis workflow.
- Practice feature engineering, model evaluation, and Python-based NLP development.

## 🔮 Future Improvements

- Explore advanced text representation techniques.
- Experiment with additional machine learning models.
- Evaluate models on larger and more diverse datasets.
- Explore transformer-based NLP models.
- Improve project documentation and add more practical NLP applications.

## 👨‍💻 Author

**Aman Raj**

- GitHub: [aman-raj-9](https://github.com/aman-raj-9)

---

If you find this repository useful for learning NLP, feel free to explore the notebooks and suggest improvements.
