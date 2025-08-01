# Movie Success Predictor

A machine learning project that predicts whether a movie is likely to be successful or not based on its metadata such as genre, runtime, language, director, and IMDb ratings. Built with scikit-learn and trained using real-world movie data.

---

## Overview

- **Problem Type**: Binary Classification  
- **Goal**: Classify movies as "Good" (IMDb ≥ 7) or "Bad"  
- **Accuracy Achieved**: ~88%  
- **Core ML Model**: Random Forest Classifier  
- **Tech Stack**: Python, Pandas, NumPy, Scikit-learn  
- **Development Environment**: Google Colab  

---

## Features Used

- Runtime  
- Genre  
- Language  
- Country  
- Director  
- Actors  
- IMDb Rating  

---

## Project Structure

```bash
movie-success-predictor/
│
├── data/                  # movie metadata
├── models/                # Saved RandomForestClassifier model (model.pkl)
├── notebooks/             
│   └── movie_success_predictor.ipynb # Jupyter/Colab notebook
├── requirements.txt       # List of dependencies
└── README.md              # Documentation

```



## How to Run
### Clone the repository
```bash
git clone https://github.com/yourusername/movie-success-predictor.git
cd movie-success-predictor
```
### Install dependencies

```bash
pip install -r requirements.txt
```
## Open the notebook in Jupyter or Google Colab
```notebooks/movie_success_predictor.ipynb```
Run all cells to preprocess data, train model, and evaluate.

### Output Sample
Classifier Used: RandomForestClassifier

Threshold Logic: IMDb rating ≥ 7 is classified as “Good”

Result: Achieved ~88% accuracy with +12% gain using sentiment integration

### Dependencies
- **pandas**

- **numpy**

- **scikit-learn**

- **matplotlib**

- **seaborn**

# Author
### Sabbir Ahmad
### [Connect on LinkedIn](https://linkedin.com/in/sabbirahmad653) | [Connect on Facebook](https://www.facebook.com/sabbir.ahmad.443854/)



#### <i style="color:gray;">Feel free to fork or star this repo if it helps you.</i><br><b style="color:green;">Contributions welcome!</b>

