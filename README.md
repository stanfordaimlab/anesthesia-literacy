# Anesthesia Literacy Project
Adaptive patient education using large-language models

# Overview 
This study explores the potential of Large Language Models (LLMs) like OpenAI's Generative Pretrained Transformer (GPT) versions 3.5 and 4 to enhance the readability of preoperative patient instructions, aiming to align them with the American Medical Association's recommendation of a 6th-grade reading level. Acknowledging that nearly 40% of U.S. adults possess basic or below basic health literacy, and the existing discrepancy between patient literacy and the complexity of medical instructions, this research investigates the use of LLMs to address this gap. We compared standard preoperative instructions from a major academic medical center with versions enhanced by GPT-3.5 and GPT-4, targeting a 6th-grade reading level. The study used a range of readability assessment formulas, including the Flesch-Kincaid Grade Level, for evaluation. Our results indicated that GPT-4 significantly outperformed both the baseline texts and GPT-3.5 in producing instructions that were consistently under the 6th-grade reading level without compromising the accuracy or comprehensiveness of the content. This finding underscores the potential of LLMs in improving patient comprehension of medical instructions, thereby contributing to better healthcare outcomes. The study, however, highlights the need for further research in diverse languages and in developing HIPAA-compliant, open-source LLMs that can be integrated into electronic health records for broader applicability in personalized perioperative medicine.


# Repository

This repo contains:
- script to convert AVS into enhanced versions (main.ipynb)
- script to perform reability analysis
- script to prepare accuracy analysis for human validation
  - validation occured on notion documents [available here](https://stanfordaimlab.notion.site/Accuracy-Completion-Assessment-f01cf8fc19c9451e9f737c1d395a901b)
  - results of validation included in accuracy-assessment folder

# Installation instructions

- clone repo
```bash
git clone https://github.com/stanfordaimlab/anesthesia-literacy.git
```
- install requirements
```bash
pip install -r requirements.txt
```
- run notebooks
```bash
cd anesthesia-literacy
jupyter main.ipynb
```
