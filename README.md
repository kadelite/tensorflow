Perfect! Let’s tackle **Part 1: Theoretical Understanding** step by step.

---

## ✅ **Part 1: Theoretical Understanding (40%)**

---

### **1. Short Answer Questions**

#### **Q1: Explain the primary differences between TensorFlow and PyTorch. When would you choose one over the other?**

**Answer:**
TensorFlow and PyTorch are both powerful deep learning frameworks, but they differ in design and usage.

| Feature                   | TensorFlow                                                                                                 | PyTorch                                                 |
| ------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| **Execution Style**       | Static computation graph (via `tf.Graph` and `tf.Session`) – though newer versions support eager execution | Dynamic computation graph (eager by default)            |
| **Syntax**                | More verbose, graph-oriented                                                                               | Pythonic and intuitive                                  |
| **Debugging**             | Harder to debug (graph abstraction)                                                                        | Easier to debug (native Python support)                 |
| **Deployment**            | TensorFlow Lite & TensorFlow\.js make deployment to mobile/web easier                                      | Deployment tools like TorchScript exist but less mature |
| **Community & Ecosystem** | Very mature, strong production support (especially in Google products)                                     | Popular in research and academia                        |

**When to Choose:**

* Choose **TensorFlow** for production-ready, scalable applications, especially when deploying on multiple platforms (mobile, web, etc.).
* Choose **PyTorch** for rapid prototyping, research projects, or when readability and flexibility matter most.

---

#### **Q2: Describe two use cases for Jupyter Notebooks in AI development.**

**Answer:**

1. **Exploratory Data Analysis (EDA):**

   * Jupyter allows data scientists to load, visualize, and analyze datasets interactively using libraries like `pandas`, `matplotlib`, and `seaborn`.

2. **Model Development & Experimentation:**

   * Developers can iteratively build, train, and evaluate machine learning models in cells, seeing outputs instantly, which is ideal for testing models or hyperparameters.

---

#### **Q3: How does spaCy enhance NLP tasks compared to basic Python string operations?**

**Answer:**
While basic Python string operations can manipulate text, **spaCy** provides advanced Natural Language Processing features out-of-the-box, including:

* **Tokenization, Part-of-Speech (POS) tagging, Named Entity Recognition (NER):** spaCy understands grammar and structure.
* **Pre-trained models:** spaCy uses statistical models that understand context better than `split()` or `find()`.
* **Pipeline architecture:** It processes texts efficiently in stages with built-in or custom components.

Example: spaCy can recognize `"Apple"` as a company, whereas string methods would just treat it as text.

---

### **2. Comparative Analysis**

#### **Compare Scikit-learn and TensorFlow in terms of:**

---

| Criteria                      | **Scikit-learn**                                                         | **TensorFlow**                                                                 |
| ----------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| **Target Applications**       | Classical ML algorithms (e.g., decision trees, SVM, logistic regression) | Deep learning and neural networks                                              |
| **Ease of Use for Beginners** | Very beginner-friendly, simple syntax                                    | Steeper learning curve, especially for model architecture and training loops   |
| **Community Support**         | Strong community, excellent documentation for classical ML               | Very large community, extensive documentation and resources, especially for DL |

---


