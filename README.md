# 🤖 Artificial Intelligence Internship – Codec Technologies

> **1 Month Internship | Web Developer Intern | AICTE & ICAC Approved**

---

## 📌 Repository

```text
2025-2029_lekisha_25scs1003001466_3rd_2cse27
```

This repository documents my **learning journey, technical skills, internship experience, and project work** completed during my **1 Month Internship at Codec Technologies Pvt. Ltd.**

---

## 🏢 Internship Overview

I completed a **1 Month Internship** at **Codec Technologies Pvt. Ltd.** from **01 July 2026 to 30 July 2026** in the role of **Web Developer Intern**.

The internship was conducted through a **Pan-India Hybrid Program** and was **AICTE & ICAC Approved**. It focused on developing practical, industry-oriented skills through training, technical tasks, problem-solving activities, and project development.

```text
┌──────────────────────────────────────────────────────┐
│                  INTERNSHIP DETAILS                  │
├──────────────────────┬───────────────────────────────┤
│ Organization         │ Codec Technologies Pvt. Ltd.  │
│ Role                 │ Web Developer Intern          │
│ Duration             │ 01 July – 30 July 2026        │
│ Mode                 │ Pan India – Hybrid            │
│ Internship Type      │ AICTE & ICAC Approved         │
│ Reporting            │ Assigned Project Head(s)      │
└──────────────────────┴───────────────────────────────┘
```

The internship was designed to provide exposure to **industry-level knowledge, practical implementation, project development, and technical problem-solving**.

---

## 🎯 Internship Objectives

The major objectives of the internship were:

* To bridge the gap between **academic learning and practical implementation**
* To understand real-world technical workflows
* To improve programming and problem-solving skills
* To gain practical exposure to **Python and Machine Learning**
* To understand data preprocessing and analysis
* To build and evaluate machine-learning models
* To develop debugging and troubleshooting abilities
* To improve technical documentation and project presentation

---

# 📚 What I Learned During the Internship

## 1. 💻 Practical Development Workflow

One of my major learnings was understanding how a technical project progresses from an initial idea to a working solution.

I learned to:

* Break complex problems into smaller tasks
* Plan the implementation process
* Experiment with different approaches
* Test and validate solutions
* Debug errors
* Improve the final implementation

This helped me develop a more **structured and systematic approach to technical problem-solving**.

---

## 2. 📝 Understanding Project Requirements

The internship helped me understand how project requirements are converted into technical tasks.

Rather than focusing only on theoretical concepts, I learned to consider:

```text
Requirements
     ↓
Planning
     ↓
Implementation
     ↓
Testing
     ↓
Evaluation
     ↓
Improvement
     ↓
Documentation
```

This gave me a better understanding of how practical technical projects are developed.

---

## 3. 🛠️ Problem Solving & Debugging

Technical tasks provided valuable experience in identifying and solving problems.

I improved my ability to:

* Analyze errors
* Identify possible causes
* Test different solutions
* Modify unsuccessful approaches
* Validate results
* Optimize implementations

This strengthened my **logical thinking and debugging skills**.

---

## 4. 🐍 Python & Machine Learning

During the internship, I gained practical exposure to **Python-based development and machine-learning workflows**.

I learned about:

* Dataset handling
* Data cleaning
* Exploratory Data Analysis
* Text preprocessing
* Feature extraction
* Model training
* Model comparison
* Performance evaluation

The experience helped me understand how programming and machine learning concepts can be combined to solve real-world problems.

---

## 5. 📊 Data Processing & Evaluation

Working with datasets helped me understand the importance of preparing data before training a model.

The general workflow followed was:

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Text Preprocessing
     ↓
Feature Extraction
     ↓
Train/Test Split
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Optimization
```

I also learned that model development does not end after training. Different algorithms and configurations need to be compared using suitable evaluation metrics.

---

## 6. 📖 Documentation & Professional Skills

Another important aspect of the internship was learning how to document technical work clearly.

I gained experience in:

* Organizing project files
* Recording results
* Explaining technical processes
* Presenting project outcomes
* Writing structured documentation
* Communicating technical concepts clearly

These skills are important for working effectively in professional development environments.

---

# 🚨 Project: SMS Spam Detection

As part of my technical work during the internship, I developed a **Machine Learning-based SMS Spam Detection System**.

### 🎯 Objective

The primary objective of the project was to automatically classify SMS messages into two categories:

```text
┌─────────────────────┐
│      SMS MESSAGE    │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│ Text Preprocessing  │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│   TF-IDF Features   │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│ Machine Learning    │
│       Model         │
└──────────┬──────────┘
           ↓
     ┌─────┴─────┐
     ↓           ↓
   HAM         SPAM
```

---

# 🔬 Project Workflow

The project involved several stages of data processing and machine learning.

### 1. Dataset Preparation

The dataset initially contained:

```text
Total Records: 5,572
```

After removing duplicate records and unnecessary data:

```text
Final Records: 5,169

Ham Messages  : 4,516
Spam Messages :   653
```

---

### 2. 🧹 Data Cleaning

The dataset was cleaned by:

* Removing duplicate records
* Removing unnecessary columns
* Handling the required data fields
* Preparing the dataset for further analysis

---

### 3. 📈 Exploratory Data Analysis

Exploratory analysis was performed to understand:

* Distribution of Ham and Spam messages
* Dataset characteristics
* Text patterns
* Class imbalance
* Important properties of the messages

---

### 4. 🔤 Text Preprocessing

The SMS messages were transformed into a suitable format for machine learning.

The preprocessing process included:

```text
Raw Text
   ↓
Tokenization
   ↓
Stopword Removal
   ↓
Stemming
   ↓
Clean Text
```

---

### 5. 🔢 TF-IDF Feature Extraction

The cleaned text was converted into numerical features using **TF-IDF (Term Frequency–Inverse Document Frequency)**.

```text
Text Data
    ↓
TF-IDF Vectorization
    ↓
Numerical Feature Matrix
    ↓
Machine Learning Models
```

This allowed machine-learning algorithms to process the textual information.

---

# 🤖 Machine Learning Models

Multiple algorithms were trained and compared during the project.

Some of the algorithms tested included:

| Algorithm                       |
| ------------------------------- |
| Naive Bayes                     |
| Extra Trees                     |
| Random Forest                   |
| Support Vector Classifier (SVC) |
| Logistic Regression             |
| AdaBoost                        |
| XGBoost                         |
| Ensemble Models                 |

The models were evaluated using metrics such as:

* **Accuracy**
* **Precision**

---

# 🏆 Best Model Result

The strongest recorded result was obtained using a **Soft Voting Classifier** combining:

```text
SVC
  +
Multinomial Naive Bayes
  +
Extra Trees
```

### 📊 Performance

```text
┌───────────────────────────────┐
│       MODEL PERFORMANCE       │
├───────────────────────────────┤
│ Accuracy  : 98.16%            │
│ Precision : 99.17%            │
└───────────────────────────────┘
```

This experiment demonstrated how combining multiple machine-learning models can improve classification performance.

---

# 💡 Key Internship Takeaways

Through this internship, I developed a stronger understanding of:

```text
✓ Practical Programming
✓ Python Development
✓ Data Cleaning
✓ Exploratory Data Analysis
✓ Text Preprocessing
✓ TF-IDF Feature Extraction
✓ Machine Learning
✓ Model Training
✓ Model Evaluation
✓ Ensemble Learning
✓ Debugging
✓ Technical Documentation
```

More importantly, I learned how to approach technical problems with a **practical and solution-oriented mindset** rather than relying only on theoretical knowledge.

---

# 🧠 Skills Developed

### Technical Skills

| Category            | Skills                                   |
| ------------------- | ---------------------------------------- |
| Programming         | Python                                   |
| Data Processing     | Data Cleaning, Preprocessing             |
| Data Analysis       | Exploratory Data Analysis                |
| NLP                 | Tokenization, Stopword Removal, Stemming |
| Feature Engineering | TF-IDF                                   |
| Machine Learning    | Classification Algorithms                |
| Model Evaluation    | Accuracy, Precision                      |
| Ensemble Learning   | Soft Voting Classifier                   |
| Development         | Debugging & Testing                      |
| Documentation       | Technical Documentation                  |

---

# 📜 Certificate

The internship certificate confirms the successful completion of the **1 Month AICTE & ICAC Approved Internship Program** at **Codec Technologies Pvt. Ltd.**

```text
Internship Role : Web Developer Intern
Organization    : Codec Technologies Pvt. Ltd.
Duration        : 01 July 2026 – 30 July 2026
Program         : AICTE & ICAC Approved
```

---

# 🎓 Overall Learning

The internship provided an opportunity to move beyond classroom-based theoretical learning and gain practical experience in technical project development.

The combination of:

```text
Training
   +
Technical Tasks
   +
Project Development
   +
Data Analysis
   +
Machine Learning
   +
Model Evaluation
   +
Documentation
```

helped me build a stronger foundation in **Python, data analysis, machine learning, and practical software development workflows**.

---

# 🚀 Future Scope

The knowledge and experience gained during this internship will help me explore future opportunities in:

* Web Development
* Python Development
* Data Analysis
* Machine Learning
* Natural Language Processing
* Artificial Intelligence
* Software Development

I aim to continue improving my technical skills by working on more real-world projects and exploring advanced machine-learning and AI technologies.

---

# 🙏 Acknowledgement

I sincerely thank **Codec Technologies Pvt. Ltd.** for providing me with this internship opportunity and for giving me a platform to develop practical technical skills.

I am also grateful to the **project and training team** for their guidance and support throughout the internship.

This experience has been an important step in my technical learning journey and has motivated me to continue exploring the fields of **Artificial Intelligence, Machine Learning, Python, and Software Development**.

---

## 👩‍💻 Intern

```text
Name       : Lekisha
Organization: Codec Technologies Pvt. Ltd.
Role       : Web Developer Intern
Duration   : 01 July 2026 – 30 July 2026
```

---

## ⭐ Conclusion

> **The internship transformed theoretical knowledge into practical experience and helped me develop the technical, analytical, and problem-solving skills required to approach real-world projects with confidence.**

---

### 📌 Repository Highlights

```text
📁 Internship Documentation
📁 Machine Learning Project
📊 Dataset Analysis
🤖 SMS Spam Detection
📈 Model Evaluation
📝 Technical Learnings
🏆 Internship Certificate
```

**Thank you for visiting this repository!** 🚀
