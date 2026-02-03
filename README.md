# ViMSTox – Vietnamese Middle School Toxicity Dataset

## 1. Introduction
**ViMSTox** is a Vietnamese-language dataset developed to support research on **toxic and inappropriate language detection** in **educational assistant systems (chatbots)** designed for **middle school students (Grades 6–9)**.

This repository accompanies the master’s thesis:

> **Research and Development of Toxic Language Detection Models for Educational Assistant Systems Targeting Middle School Students**  
> **Author:** Diep Thi Thanh Thao  
> **Supervisor:** Dr. Huynh Thai Hoc  

The research aims to enhance **content safety**, **pedagogical appropriateness**, and **responsible deployment of AI** in Vietnamese educational environments.

---

## 2. Research Motivation and Context
Conversational AI systems are increasingly integrated into educational platforms. While they improve accessibility and learning support, they also introduce **content safety risks**, especially for minors.

Most existing Vietnamese toxicity datasets are derived from **open-domain or social media data**, which differ substantially from educational interactions. In contrast, educational language is:
- Domain-specific and curriculum-oriented  
- Short, instructional, and context-dependent  
- Sensitive to pedagogical norms rather than explicit profanity  

ViMSTox addresses this gap by focusing on **toxicity and inappropriate language within middle school educational contexts**.

---

## 3. Dataset Overview
- **Language:** Vietnamese  
- **Target population:** Middle school students (Grades 6–9)  
- **Task formulation:** Binary classification  
  - `0`: Non-toxic (educationally appropriate)  
  - `1`: Toxic / Sensitive (harmful, abusive, or pedagogically inappropriate)  
- **Educational domains:** Mathematics, Literature, Informatics, Natural Sciences, History–Geography, Civic Education, Foreign Languages, and others  

The dataset is designed to support **domain-aware toxicity detection** for educational chatbot moderation.

---

## 4. Data Collection and Construction
ViMSTox is constructed through a **multi-stage, human-centered pipeline**:

1. **Survey-based data collection**  
   Structured surveys were conducted to capture perceptions of inappropriate or harmful language in middle school learning scenarios.

2. **Crawled educational data**  
   Publicly available Vietnamese educational content was collected to ensure realistic domain coverage.

3. **Expert review and validation**  
   Selected samples were reviewed by domain experts to improve labeling reliability and pedagogical alignment.

4. **Controlled synthetic augmentation**  
   Synthetic samples were generated based on survey-derived patterns to increase coverage while preserving educational relevance.

Synthetic data are used to **augment**, not replace, human-validated samples.

---

## 5. Project Status
✅ **Survey and data collection phase completed**

The project is ready for:
- Data cleaning and normalization  
- Exploratory and statistical analysis  
- Final dataset consolidation  
- Training and evaluation of toxicity detection models  
- Benchmarking and ensemble-based modeling  

---

## 6. Repository Structure
  ViMSTox/
    ├── crawled_data/ # Crawled educational queries and titles
    ├── data/ # Processed datasets and train/test splits
    ├── surveys/ # Survey instruments and reviewed survey data
    ├── index.html # Survey interface
    ├── thanks.html # Survey completion page
    ├── README.md # Project documentation

---

## 7. Ethical Considerations
The collection and use of ViMSTox strictly adhere to academic research ethics:

- Data are used **exclusively for academic research**
- **No personally identifiable information (PII)** is collected
- Data processing follows principles of:
  - Anonymization  
  - Data minimization  
  - Secure storage and controlled access  
- Toxicity is evaluated **within an educational and pedagogical context**, not general profanity detection  

---

## 8. Intended Use and Limitations
**Intended use:**
- Research on toxicity detection for educational chatbots  
- Evaluation of Vietnamese NLP models under domain-specific constraints  
- Development of content moderation mechanisms for learning environments  

**Limitations:**
- The dataset reflects Vietnamese middle school contexts and may not generalize to other age groups or cultures  
- Labels represent contextual judgments rather than absolute definitions of toxicity  

Human oversight is recommended for real-world deployment.

---

## 9. Citation
If you use or extend this dataset, please cite the corresponding research work and acknowledge the research group.

> ViMSTox – Vietnamese Middle School Toxicity Dataset  
> Faculty of Information Technology  
> University of Industry and Trade, Vietnam

---

## 10. Contact
For academic inquiries or collaboration:

**Dr. Huynh Thai Hoc**  
Faculty of Information Technology  
University of Industry and Trade, Vietnam
Email: hocht@huit.edu.vn
