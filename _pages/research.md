---
layout: single
title: "Research"
permalink: /research/
author_profile: true
classes: wide
---
## Overview
My research is at the intersection of machine learning, medical imaging, and clinical reasoning. Current models can generate fluent explanations, but they often do so without grounding their conclusions in image features or clinical logic, leading to hallucinations, overconfidence, and inconsistent diagnostic behavior.

I am currently developing VLMs that move beyond pattern-matching and can perform structured, clinically valid reasoning over radiographs and multimodal patient data. I am also studying why multimodal models hallucinate in medical settings and working on uncertainty modeling and constraint-aware decoding—to prevent incorrect or fabricated findings.

## Recent Publications
### **Nature Medicine**  
-[The fragile intelligence of GPT-5 in medicine]( https://www.nature.com/articles/s41591-025-04008-8)

### **npj Digital Medicine**  
-[A longitudinal analysis of declining medical safety messaging in generative AI models](https://www.nature.com/articles/s41746-025-01943-1)

My recent paper on the [lack of medical disclaimers in AI models](https://www.nature.com/articles/s41591-025-04008-8) was featured in:

- **The New York Times**: ["Meet Dr. ChatGPT"](https://www.nytimes.com/2025/11/16/briefing/meet-dr-chatgpt.html?unlocked_article_code=1.1k8.Q4Ac.rtVRNbAeAvPD&smid=url-share)

- **MIT Technology Review**: ["AI companies have stopped warning you that their chatbots aren't doctors"](https://www.technologyreview.com/2025/07/21/1120522/ai-companies-have-stopped-warning-you-that-their-chatbots-arent-doctors/)

- **Computerworld**: ["AI chatbots ditch medical disclaimers, putting users at risk, study warns"](https://www.computerworld.com/article/4026778/ai-chatbots-ditch-medical-disclaimers-putting-users-at-risk-study-warns.html)

## Projects

**Global Visual-Spatial Human Chain-of-Thought CXR Dataset**

- At the Stanford Artificial Intelligence in Medicine & Imaging (AIMI) Center, I am leading the development of one of the first global datasets designed to capture how radiologists think, not just what diagnoses they make. While traditional medical imaging datasets focus on labels or written reports, this project records the full cognitive and visual reasoning process behind each interpretation.
- I created a custom web-based DICOM viewer platform that collects real-time chain-of-thought explanations that is linked to visual-spatial navigation patterns as radiologists read chest X-rays. This includes the sequence of observations they make, the regions they examine point by point, and the reasoning steps that lead them to a final interpretation. We intend to publicly release this dataset and train models to be grounded in actual visual-spatial-cognitive reasoning. 
- This one of the largest global datasets, as we currently have over 300 participating radiologists from more than 70 countries.

**Real-world Internet Medical Questions Dataset**

- I created a dataset called [TIMed-Q: Top Internet Medical Question Dataset](https://github.com/sonalisharma-3/TIMed-Q)
- TIMed-Q is a curated dataset of 500 patient-phrased medical questions sourced from real-world internet searches. 
- It is designed to support research in clinical reasoning, and medical safety evaluation by capturing the authentic language and concerns of patients seeking medical information online.





