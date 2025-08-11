# **Grammar and Spell Checker**  
A natural language processing (NLP) tool designed to correct spelling and grammar errors using n-grams, Levenshtein distance, and CFG.

## **Overview**  
**Grammar and Spell Checker** focuses on improving text accuracy by detecting and correcting spelling and grammar mistakes through advanced NLP techniques. Using bigram probabilities and Levenshtein distance, it suggests the best corrections based on contextual relevance and word similarity. Additionally, grammar corrections are applied using predefined production rules.

## **Features**  
- **Spell Checking**: Detects misspellings and suggests corrections using Levenshtein distance.  
- **Contextual Error Correction**: Uses bigram probabilities to provide the most contextually accurate word replacements.  
- **Grammar Checking**: Identifies grammatical errors and rearranges words according to defined production rules.  
- **Bigram Frequency Analysis**: Computes bigram frequencies to enhance contextual error detection.  
- **Evaluation Metrics**: Utilizes precision, recall, and F1-score for performance assessment.  

## **Technologies Used**  
- **Python**: Primary language for implementation.  
- **spaCy**: Used for tokenization and linguistic analysis.  
- **NLTK**: Powers grammar parsing and syntax validation.  
- **Scikit-learn**: Provides evaluation metrics for assessing correction accuracy.  
- **Regular Expressions**: Assists in text preprocessing and punctuation handling.
