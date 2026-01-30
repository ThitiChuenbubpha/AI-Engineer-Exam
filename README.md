# AI Engineer Exam: Practical Assessment

## 🎯 Objective
This exam is designed to assess your practical skills in designing and developing AI systems. You are required to use the provided datasets to build innovative solutions using both **Traditional Machine Learning** and **Generative AI (LLMs)** technologies.

---

## 📂 Data Resources
You are provided with the following data sources:

### 📦 Product Data
| Folder | Description |
|--------|-------------|
| `/product_details` | 100 PDF files with detailed product specifications and descriptions |
| `/product_images` | Corresponding product images |
| `/sqlite_db` | SQLite database (`data.db`) with relational data (products, sales, inventory, etc.) |

### 💰 Loan Data (NEW)
| File/Folder | Description |
|-------------|-------------|
| `/Loan_data/train.csv` | Training dataset with historical loan records including default labels |
| `/Loan_data/test.csv` | Test dataset for prediction (no default labels) |
| `/Loan_data/loan_database.sqlite` | Normalized SQLite database with properly structured schema |
| `/Loan_data/db_schema.md` | Complete database schema documentation with ER diagram |
| `/Loan_data/Data Dictionary.xlsx` | Data dictionary explaining all variables |

#### Loan Database Schema Overview
```
loans (main) ─┬─ credit_scores (bureau score)
              ├─ primary_accounts (borrower's loans)
              ├─ secondary_accounts (guarantor's loans)
              ├─ account_history (credit history)
              └─ lookup tables (states, branches, suppliers, manufacturers, risk_categories)
```


---

## 🛠️ Project Requirements

### Core Requirements
Develop **at least TWO AI systems** that leverage the provided data:

| # | Type | Description | Example Use Cases |
|---|------|-------------|-------------------|
| 1 | **Traditional ML** | Apply classic ML techniques | Classification, Regression, Clustering, Recommendation, Forecasting, Anomaly Detection |
| 2 | **Generative AI (LLMs)** | Leverage Large Language Models | RAG, Multi-Agent System, Chatbot, Content Generation, Text-to-SQL, Document QA |

### Flexibility
- ✅ **No restrictions** on programming languages, frameworks, or tools
- ✅ Create **as many projects as you want** (minimum 2)
- ✅ Choose **any combination** of provided datasets
- ✅ Use **any technology stack** (Python, JavaScript, Rust, LangChain, LlamaIndex, Scikit-learn, PyTorch, etc.)

> [!NOTE]
> You are **not required** to use all provided data. Select datasets relevant to your proposed solutions.

---

## 📄 Deliverables

Submit a **comprehensive report** (PDF) for all projects containing:

### 1. Idea & Concept
- Problem statement and context
- Value proposition and business impact
- Target users and use cases

### 2.  System Design
- Architecture diagram (data flow, components)
- Technology stack justification
- Model/algorithm selection rationale
- Data preprocessing and feature engineering approach

### 3.  Results & Demonstration
- Model performance metrics (accuracy, F1, AUC, etc.)
- Sample outputs, predictions, or generated content
- Screenshots or video demonstrations
- Insights and findings from the data

### Example Project Ideas

#### Traditional ML (Loan Data)
| Project | Description |
|---------|-------------|
| **Loan Default Prediction** | Binary classification to predict loan defaults |
| **Credit Risk Scoring** | Custom scoring model based on credit features |
| **Customer Segmentation** | Clustering borrowers by risk profiles |
| **LTV Optimization** | Regression model to optimize loan-to-value ratios |

#### Generative AI (Product + Loan Data)
| Project | Description |
|---------|-------------|
| **Product QA Chatbot** | RAG-based chatbot for product information queries |
| **Text-to-SQL Agent** | Natural language interface for loan database queries |
| **Document Summarizer** | LLM-powered product description summarization |
| **Multi-Agent Analyst** | AI agents collaborating on data analysis tasks |

---


---

**Good luck! We look forward to seeing your creativity and engineering skills.** 🚀
