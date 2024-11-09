# Email Threat Analysis Tool

## Overview

The **Email Threat Analysis Tool** is a Python-based Colab notebook designed to analyze email headers, subjects, and content for potential security threats. This tool uses a large language model 
from ollama to assess the likelihood of phishing attempts and flags suspicious elements within emails. 

## Features

- **Phishing Probability Assessment**: Evaluates each email as `low`, `medium`, or `high` risk for phishing.
- **Suspicious Element Detection**: Identifies elements like mismatched sender information, unusual phrases, or suspicious URLs.
- **Action Recommendations**: Suggests specific actions based on the analysis, such as flagging the email or alerting the user.
- **Explanation of Findings**: Provides context for each flagged item to improve understanding of the potential threat.

## Getting Started

### Installation

1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/).
2. Run the initial cells to install necessary libraries and set up the environment.

### Usage

1. **Load Email Data**: Input email headers, subject, and content into the notebook cells as directed.
2. **Run the Analysis**: Execute cells to process the email data and generate an analysis.
3. **View Results**: Review the outputs, which provide risk levels, flagged elements, and suggested actions.

### Outputs

- **Phishing Probability**: Each email is labeled with a probability level (low, medium, high) indicating the likelihood of phishing.
- **Suspicious Elements**: Specific elements in the email that may signal a threat are highlighted, along with reasons.
- **Recommended Actions**: Practical steps based on the findings, such as blocking the sender or further investigation.
- **Explanation**: Clear explanations for each flagged element, helping to contextualize the threat.
