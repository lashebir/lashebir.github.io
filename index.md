---
title: "Leah Ashebir"
---

<!-- Add buttons inside the header -->
<script>
  document.addEventListener("DOMContentLoaded", function () {
    const header = document.querySelector('.page-header');
    if (header) {
      const btnWrapper = document.createElement('div');
      btnWrapper.className = 'header-buttons';
      btnWrapper.innerHTML = `
        <a href="mailto:ltashebir77@gmail.com" class="btn header-btn">📧 Email</a>
        <a href="https://www.linkedin.com/in/leah-ashebir" class="btn header-btn">🔗 LinkedIn</a>
      `;
      header.appendChild(btnWrapper);
    }
  });
</script>

<link rel="stylesheet" href="/assets/css/style.scss">

# Hi there 👋
My name is Leah. I am a statistician and data scientist passionate about using machine learning to unlock hidden potential in data. My approach is deeply rooted in leveraging the theoretical underpinnings of machine learning technique to customize the solution to the data, not the other way around. I am excited to continue applying my skills, developing my data science / machine learning repetoire, and creating real-world impact

When I am not working on my projects, you can find me line dancing, reading about ancient cultures, or practicing my German!

# Projects 💡
## [Greco-Roman CNN Image Classification](https://github.com/lashebir/grecoroman-imageclassification)
  - Deployed an image classification model in TensorFlow/Keras to categorize classical art by depicted deity across mediums
  - Designed a custom data pipeline to label, resize, and augment model training image data
  - Achieved **89% accuracy**; presented model output and visual summaries to support interpretability for stakeholders
    
## [German→English Seq2Seq Transformer](https://github.com/lashebir/de-en-translator)
  -  Built a translation model using a custom Seq2Seq Transformer architecture in PyTorch for sentence-level prediction
  - Implemented subword tokenization **(SentencePiece)** to improve semantic consistency and recognize rare/compound words
  - Evaluated using BLEU and token-level F1; delivered annotated examples to illustrate how model decisions aligned with
grammatical structure

# Education 🎓
## University of San Francisco
- Master of Science in **Data Science**, Class of 2025
- Cohort Ambassador
  
## Indiana University Bloomington, Kelley School of Business
- Bachelor of Science in **Finance, Business Analytics**
- Business German Certificate

# Technical Skills 🧠
## Programming
Python, SQL, NoSQL

## Machine Learning & Modeling
Supervised/Unsupervised Machine Learning, Regression, Classification, **Functional
Modeling**, XGBoost/LightGBM, **Deep Learning/Transformers** (CNN, Word2Vec, Seq2Seq, Attention), Bayesian Modeling,
Random Forest, **Drift Detection** (KS, Chi-squared), End-to-end ETL data pipeline development, SentencePiece, PyTorch, NumPy, pandas, scikit-learn, SciPy, Selenium, **BeautifulSoup**, scikit-FDA, statsmodels

## Big Data & Cloud
PySpark, SparkSQL, **MongoDB**, PostgreSQL, Snowflake, Docker, Kubernetes, Terraform/GCP, Git/GitHub

## Web Experimentaiton
Causal Inference, A/B Testing, **Hypothesis Testing**, Statistical Inference, Experimental Design

## Apps & Tooling
Streamlit, **LangChain**, Unix/Linux, Excel
  
## Visualization
Matplotlib, seaborn

# Professional Experience 💻
## Research Data Scientist / Machine Learning Engineer
  - Designed **statistical learning pipelines** to predict cochlear synapse distributions using auditory brainstem response (ABR)
time-series data from **100+ subjects**
  - Modeled synaptic distributions with Random Forest, Functional Linear, and **Bayesian Profile** models;
performed multimodal signal and image feature extraction
  - Prototyped a Graph Attention Network **(PyTorch)** to fuse spatial cochlear imaging and temporal ABR signals for
diagnostic prediction


## Senior Data Consultant - Ernst & Young LLP, Technology Consulting
  - Promoted early to Senior for **exceptional client metrics** and internal performance reviews
  - **Led a global analyst team** to validate and standardize credit risk data pipelines; delivered reusable architecture that drove
$1.5M in add-on revenue and enabled expansion to new clients, strengthening long-term account relationships
  - Delivered firm-sponsored Python analytics trainings (pandas, seaborn, matplotlib) for 15–20 cross-functional analysts


## Staff Data Consultant - Ernst & Young LLP, Business Consulting
  - Drove **cross-functional stakeholder alignment** to translate regulatory policy into technical data requirements for a
market risk platform
  - Executed **root-cause analysis** of reporting discrepancies in large-scale financial pipelines; remediated retail bank issues across
multiple teams
  - Selected for **leadership rotation** in Assurance-Audit; conducted financial audits and translated German regulatory
documents for compliance use
