# ai-career-path-predictor
 AI Career Path Predictor using Resume and NLP

This project recommends top-matching job roles based on a user's resume using NLP techniques like TF-IDF vectorization and cosine similarity.

 How It Works
- Preprocesses job descriptions and resumes (stop words, lowercasing, punctuation removal).
- Converts text to TF-IDF vectors.
- Compares resume against job roles using cosine similarity.
- Outputs top 3 matching career paths.

Technologies
- Python
- Pandas
- scikit-learn
- NLTK
- spaCy

How to Run
1. Clone the repo
2. Install dependencies:
pip install -r requirements.txt
3. Place your resume in the `resume/` folder
4. Run the script:
