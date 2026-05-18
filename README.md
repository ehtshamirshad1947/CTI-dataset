# Hybrid Feature Cybersecurity Dataset

## Overview

This repository contains a hybrid cybersecurity dataset designed for:

- Threat intelligence research
- Cyber threat attribution (CTA)
- Machine learning classification
- Security analytics
- Malware behavior studies
- Adversary profiling
- Attack pattern analysis

The dataset combines multiple cybersecurity-related attributes including attacker motivations, malware types, tools, TTPs, target information, and operational details.

---

## Dataset Information

| Attribute | Description |
|---|---|
| Dataset Type | Structured Cybersecurity Dataset |
| Format | CSV |
| Records | 26,930 |
| Features | 14 |
| Domain | Cyber Threat Intelligence |

---

## Features Included

The dataset contains the following fields:

| Column Name | Description |
|---|---|
| Motivation | Reason behind the cyber attack |
| First Seen | First observed year of activity |
| Operation Performed | Type of cyber operation executed |
| Sponsor By | Sponsoring entity or actor category |
| Origing Country | Origin country of attacker |
| Outcome | Impact/result of the attack |
| Attacker skills | Skill level/type of attacker |
| TTP | Tactics, Techniques, and Procedures |
| Tools | Offensive tools used |
| Malware | Malware family/type |
| Target Country | Victim country |
| Target Organization | Victim organization category |
| Target Application | Targeted application/infrastructure |
| CTA | Cyber Threat Attribution label |

---

## Example Use Cases

- Threat actor classification
- Intrusion detection research
- Cyber attribution modeling
- AI-based cybersecurity analytics
- Malware prediction systems
- Threat hunting simulations
- Security awareness training

---

## File Structure

```text
.
├── hybrid feature dataset.csv
├── README.md
└── LICENSE
```

---

## Sample Record

| Motivation | Malware | Tools | CTA |
|---|---|---|---|
| Political ideology | Keylogger | Empire | DeepPanda |

---

## Technologies Suitable for Analysis

This dataset can be used with:

- Python
- Pandas
- Scikit-learn
- TensorFlow
- PyTorch
- XGBoost
- Jupyter Notebook

---

## Example Loading Code

```python
import pandas as pd

df = pd.read_csv("hybrid feature dataset.csv")

print(df.head())
```

---

## Research Applications

This dataset may support research in:

- Cyber threat attribution
- Adversarial AI
- Threat intelligence automation
- Behavioral analytics
- Malware ecosystem analysis
- Attack surface modeling

---

## Disclaimer

This dataset is intended strictly for:

- Educational purposes
- Academic research
- Defensive cybersecurity research

Do not use this dataset for malicious activities.

---

## License

Choose an appropriate license before public release.

Recommended options:

- MIT License
- CC BY 4.0
- Apache 2.0

---

## Author

Add your name or organization here.
