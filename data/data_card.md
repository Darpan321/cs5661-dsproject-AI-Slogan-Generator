
# Dataset Name: AI Slogan Generator

This dataset supports the development of a deep learning model that automatically generates creative and relevant slogans based on a brand name or industry category. The data, sourced from Kaggle, includes slogans from real-world companies, capturing how different industries frame their messaging. The goal is to build a sequence generation model (e.g., LSTM, Transformer) that can replicate these patterns.

## Dataset Link
https://www.kaggle.com/datasets/chaibapat/slogan-dataset

## Data Card Author(s)
- Yash Sohagia, CSULA, (Owner)
- Darpan Patel, CSULA, (Contributor)
- Jay Bambhroliya, CSULA, (Contributor)

## Publishers
California State University, Los Angeles (CSULA)

## Industry Type(s)
- Academic - Tech

## Dataset Overview
### Data Subject(s)
- Non-Sensitive Data about people
- Data about systems or products and their behaviors

### Dataset Snapshot
Category | Data
--- | ---
Size of Dataset | ~500 KB
Number of Instances | ~9,000 slogans
Number of Fields | 3 (Brand, Industry, Slogan)
Labeled Classes | N/A
Number of Labels | N/A
Average Labels Per Instance | N/A
Algorithmic Labels | None
Human Labels | Yes
Other Characteristics | Text data with categorical context

### Content Description
Each entry includes a brand or company name, an industry category, and a corresponding slogan. This structured format enables model training for text generation conditioned on input features like category or brand name.

## Sensitivity of Data
- Anonymous Data
- None of the records contain PII

## Security and Privacy Handling
All data is scraped or compiled from public sources and made available on Kaggle for educational use. No identifiable or sensitive personal information is included.

## Transformation(s) Applied
- Cleaning Missing Values
- Deduplication
- Tokenization for model input
- Lowercasing and Unicode normalization

## Primary Data Modality
- Tabular Data
- Text Data

## Annotations & Labeling
- Human Annotations: All slogans were human-authored originally and paired with brand/context by dataset creators

## Intended Use
- AI-assisted slogan generation
- NLP research in text generation
- Creative tools for marketing/branding teams

## Limitations & Tradeoffs
- Limited diversity across global markets
- Bias toward specific industries or cultural framing
- Not updated to include slogans post-2023

## Version and Maintenance
- Version: 1.0
- Status: Static
- Last Updated: 04/2025
- Next Update: None scheduled

## Tools Used
- Python, pandas
- LSTM, Transformer (planned)
- Google Colab

## Known Correlation(s)
- Certain industries (e.g., food, tech) show distinct slogan patterns
- Frequent use of imperative tone (e.g., "Just do it")

## Risk Type(s)
- No Known Risks

---

*This Data Card was created based on the extended template from the [Google Data Cards Playbook](https://sites.research.google/datacardsplaybook/).*
