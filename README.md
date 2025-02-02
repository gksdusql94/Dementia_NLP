# Dementia Voice Biomarkers - Sentence Construction Analysis

This project focuses on **sentence construction analysis** in dementia patients using NLP techniques.  
I was responsible for analyzing the **sentence-level linguistic patterns** within the larger study.

## 📌 Project Overview
This study analyzes sentence construction tasks performed by a **dementia patient group**.  
Participants were given specific words (e.g., "pencil", "tree", "child, hospital") and were asked to form a **simple sentence** using those words.  
The words **did not have to be used in the given order**.

### **Analysis Features (Task-Specific)**
| Feature | Cognitive Construct |
|---------|----------------------|
| Number of missing tasks per participant | N/A |
| Number of correct complete sentences | Verbal Expression |
| Number of complete sentences **not using** the provided words | Verbal Expression |
| Number of incomplete sentences (missing a subject, verb, or object) | Grammar, Telegraphic Speech |
| Number of grammatical errors | Grammar |
| Number of repeated words **without forming a sentence** | Echolalia |
| Number of repeated attempts to construct a sentence with the same words | Verbal Expression |
| Number of filler words (e.g., "um") | Word-Finding Difficulties |
| Mean speech rate | Language |

## 📂 Project Files
- `Sentence_2025.ipynb` : Analysis of 2025 dataset and sentence construction patterns  
- `Sentence_2024.ipynb` : Analysis of 2024 dataset and sentence modeling  
- `(YB)Sentence_annot_minor_list_.ipynb` : Sentence-level annotation (minor features)  
- `(YB)annot_major_sentence_.ipynb` : Major sentence pattern analysis and annotation  

## 🛠️ Technologies Used
- **Python Libraries**: SpaCy, Hugging Face, NLTK, Pandas  
- **NLP Techniques**: Sentence-level linguistic pattern analysis
- **Dataset**: Dementia Bank
- 
## 📈 Research Goals
This research aims to quantitatively analyze sentence construction patterns in dementia patients using NLP techniques.
By examining grammatical errors, filler words, and repeated attempts, this study contributes to early diagnosis models for dementia.

## 🔧 Installation
```bash
pip install -r requirements.txt
