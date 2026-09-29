# The Impact of AI Tools on Students' Python Learning Performance
[![Metadata Standard: DDI](https://img.shields.io/badge/Metadata_Standard-DDI_3.3-blue.svg)](https://ddialliance.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
##  Project Overview
This dataset contains learning analytics logs collected from an introductory Python programming course. The primary objective of this research project is to analyze how the integration of Generative AI tools (such as ChatGPT and Gemini) impacts graduate students' Python learning behaviors, code debugging habits, assignment submission patterns, and final academic performance.

##  Researcher Information
**Author:** Shihao Cheng(Seven)
* **ORCID ID:** https://orcid.org/0009-0007-4430-5040
* **Dataset DOI:** `10.5281/zenodo.1234567` *(Hypothetical)*
* **Institution:** Columbia University in the City of New York

##  Metadata Standard
This dataset's metadata is documented following the **Data Documentation Initiative (DDI)** standard (DDI-Codebook/DDI-Lifecycle). DDI is the widely accepted standard for describing social science, behavioral, and educational data, ensuring that variables, data collection procedures, and access parameters are machine-readable and interoperable.

---

##  Data Dictionary

The dataset is saved as a structured CSV file (`python_ai_learning_analytics.csv`). Below is the complete data dictionary defining each variable attribute:
| Variable Name | Data Type | Measurement Unit / Format | Description | Value Range / Examples |
| :--- | :--- | :--- | :--- | :--- |
| `student_id` | String | Categorical | Anonymized unique identifier for each student | `STU_01` - `STU_02` |
| `course_section` | String | Categorical | Python programming course section code | `HUDM_5001_FALL` |
| `ai_prompt_count` | Integer | Count | Total number of prompts submitted to AI coding assistants during the term | $0 \le x \le 500$ |
| `ai_assisted_hours` | Float | Hours | Cumulative hours spent using AI tools during Python programming tasks | $0.0 \le x \le 80.0$ |
| `code_submissions` | Integer | Count | Total number of Python code submission attempts in the automated grading platform | $1 \le x \le 300$ |
| `assignment_avg_score` | Float | Score (0–100) | Average percentage score achieved across all Python coding assignments | $0.0 \le x \le 100.0$ |
| `average_python_grade` | Float | Score (0–100) | Average of Mid and Final grade awarded in the introductory Python programming course | $0.0 \le x \le 100.0$ |

---

##  Dataset Structure & Format
```text

├── README.md                           # Project metadata and data dictionary
├── LICENSE                             # MIT License file
└── data
    └── python_ai_learning_analytics.csv # Primary anonymized dataset
```
