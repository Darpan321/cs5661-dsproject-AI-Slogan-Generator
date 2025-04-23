# 📊 Data Card: AI Slogan Generator

This dataset supports the development of a deep learning model that automatically generates creative and relevant slogans based on a brand name or industry category. The data, sourced from Kaggle, includes slogans from real-world companies, capturing how different industries frame their messaging. The goal is to build a sequence generation model (e.g., LSTM, Transformer) that can replicate these patterns.


## 📂 Dataset Summary

- Dataset Name: AI Slogan Generator
- Data Format: CSV
- Number of Records: ~9,000 slogans
- Data Source: [https://www.kaggle.com/datasets/chaibapat/slogan-dataset](https://www.kaggle.com/datasets/chaibapat/slogan-dataset)
- Collection Method: Scraped and curated from public sources

### Dataset Snapshot
| Category                    | Data                               |
| --------------------------- | ---------------------------------- |
| Size of Dataset             | ~500 KB                           |
| Number of Instances         | ~9,000 slogans                    |
| Number of Fields            | 3 (Brand, Industry, Slogan)        |
| Algorithmic Labels          | None                               |
| Human Labels                | Yes                                |
| Other Characteristics       | Text data with categorical context |

### Descriptive Statistics (Example Field: `slogan_length`)
| Statistic          | Value       |
| ------------------ | ----------- |
| Mean Slogan Length | ~5.2 words |
| Min Slogan Length  | 1 word      |
| Max Slogan Length  | ~15 words  |

### Data Card Author(s)
Team: Kinnariben Manojkumar Kotadiya, Dhruvi Desai, Palak Dave, Harita Parikh, Tushar Bhaliya, Darpan Patel


## 📄 Features Collected
- Brand (Company Name)
- Industry Category
- Slogan

## 🎯 Purpose of Dataset
To enable development of a slogan generation system using transformer-based deep learning architectures (e.g., BART). Key goals include:
- NLP-based creative text generation
- Assisting marketers and branding teams
- Academic experimentation with sequence generation models

## ⚙️ Data Collection Process & Preprocessing Summary

### Tools Used
- Python, pandas, LSTM, Transformer (planned), Google Colab
  
### Collection Method
- Slogans were sourced from publicly available branding and marketing materials.
- The dataset was curated from multiple open sources and compiled into a structured CSV file by the original contributors on Kaggle.

### Preprocessing Steps
- Removed duplicates and missing data
- Tokenized and lowercased text
- Normalized Unicode characters

## 🔒 Ethical Considerations
Uses only public, non-sensitive, human-authored slogans
No personal or identifiable information included
Intended strictly for educational and research use

### Intended Use
- Educational NLP model training
- NLP research in text generation
- Exploration of transformer performance in branding tasks

### Evaluation Metrics
- Slogan diversity & coherence (human evaluation)
- BLEU/ROUGE scores for baseline benchmarking


## ⚠️ Limitations & Tradeoffs

- Dataset skews toward Western brands and English slogans
- Output may repeat existing slogan structures due to training data bias
- No post-2023 slogan updates included in dataset

## 📦 Version and Maintenance

- Version: 1.0
- Status: Static
- Last Updated: 04/2025
- Next Update: None scheduled

## ✅ Validation

- Verified no missing values in key fields
- Removed 593 duplicates from original dataset
- Visualized slogan length distribution to inspect anomalies

## Citation Guidelines

**How to Cite:** If you use this dataset or the generated slogans in your work, please cite the Kaggle source and the project contributors:

```
Slogan Dataset. Kaggle. https://www.kaggle.com/datasets/chaibapat/slogan-dataset
Contributors: Kotadiya K., Desai D., Dave P., Parikh H., Bhaliya T., Patel D. (2025). AI Slogan Generator Project, CSULA.
```
---

*This Data Card was created based on the extended template from the [Google Data Cards Playbook](https://sites.research.google/datacardsplaybook/).*
