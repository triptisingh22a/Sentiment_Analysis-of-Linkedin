# Sentiment Analysis of Professional Social Network like Linkedin using Textblob

This repository contains the source code and data pipeline used in the research paper:

🔗 **DOI:**(DOI: 10.1109/ISED63599.2024.10956862 ) 
 *Presented at the 2024 IEEE ISED Conference*
## Abstract
In the evolving landscape of professional social networks, LinkedIn represents a key platform for career-oriented engagement and strategic networking. This project implements a structured NLP-based sentiment analysis pipeline using the **TextBlob** library to classify user-generated content—such as posts, comments, and recommendations—into **positive**, **negative**, and **neutral** sentiments.

### Key Research Hypotheses:
1. **Networking Behavior Hypothesis**: Professionals’ connections are intentional and career-driven.
2. **Content Interaction Hypothesis**: Content sentiment varies with seniority level, industry sector, and career stage.

#### Methodology
📊 Data Collection
Source: 500 LinkedIn users categorized by activity level (high, medium, low)

Tools: Web scraping (Beautifulsoup)+ JSON parsing
##### Sentiment Analysis
Library: TextBlob

Metrics:

Polarity (-1 to +1)

Subjectivity (0 to 1)

##### CITE THIS WORK
If you use this project or reference the results, please cite the IEEE paper:

@inproceedings{linkedin2024sentiment,
  author={Your Name},
  title={Analyzing Professional Networking Behavior on LinkedIn Using NLP-based Sentiment Analysis},
  booktitle={IEEE ISED},
  year={2024},
  doi={10.1109/ISED63599.2024.10956862}
}
