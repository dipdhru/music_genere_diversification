# Music Genre Classification using Big Data Analytics

A machine learning project that addresses genre ambiguity and overlap in Spotify's music categorization by combining acoustic features and lyric information.

## 📋 Project Overview

**Author:** Dipanshu Singh  
**Course:** M508 - Big Data Analytics

### Business Problem

Genre Ambiguity and Overlap in Spotify's Music Categorization presents a significant challenge:

- **Current Issue:** Many genres share similar audio characteristics (tempo, danceability, speechiness), making classification difficult
- **Examples:** Pop, EDM, and rap often exhibit overlapping features; rock and country have stylistic similarities

### Solution Approach

This project implements a multi-modal approach by:
- Merging **lyrics-based analysis** with **acoustic data**
- Creating more nuanced genre classifications
- Reducing genre overlap through advanced machine learning techniques

### Expected Impact

- Discovery of new, hybrid genres
- More diverse and accurate music recommendations
- Improved user experience through better categorization

## 🛠️ Technologies Used

- **Python 3.11+**
- **Jupyter Notebook**
- **Machine Learning Libraries:**
  - scikit-learn
  - TensorFlow/Keras (if applicable)
  - pandas, numpy
- **NLP Libraries:**
  - spaCy
  - unidecode
- **Data Visualization:**
  - matplotlib
  - seaborn

## 📊 Dataset

The project uses Spotify music data with features including:
- Audio characteristics (tempo, energy, danceability, etc.)
- Lyric information
- Genre labels

## 🚀 Getting Started

### Prerequisites

```bash
python >= 3.11
pip
jupyter notebook
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/music-genre-classification.git
cd music-genre-classification
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Download spaCy language model:
```bash
python -m spacy download en_core_web_sm
```

### Running the Project

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `M508_Final_Project_for_Big_Data_Analytics.ipynb`

3. Run the cells sequentially

## 📁 Project Structure

```
music-genre-classification/
│
├── M508_Final_Project_for_Big_Data_Analytics.ipynb  # Main analysis notebook
├── README.md                                         # Project documentation
├── requirements.txt                                  # Python dependencies
├── .gitignore                                       # Git ignore rules
└── LICENSE                                          # License file
```

## 📈 Methodology

1. **Data Collection & Preprocessing**
   - Audio feature extraction
   - Lyric processing and cleaning
   - Data normalization

2. **Feature Engineering**
   - Acoustic feature analysis
   - Text feature extraction from lyrics
   - Feature fusion techniques

3. **Model Development**
   - Multiple classification algorithms
   - Model evaluation and comparison
   - Hyperparameter tuning

4. **Results & Analysis**
   - Performance metrics
   - Genre overlap visualization
   - Insights and recommendations

## 📝 Key Findings

*(You can add your key findings here after running the analysis)*

## 🔗 References

Li, You, et al. "Music Genre Classification Based on Fusing Audio and Lyric Information." *Multimedia Tools and Applications*, 29 Dec. 2022, https://doi.org/10.1007/s11042-022-14252-6.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

