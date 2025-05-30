# Personalized Learning Models for Neurodivergent Students

This project investigates how student engagement data can be used to develop personalized curriculum pathways, with a focus on potential future applications for neurodivergent learners (e.g., students with ADHD or autism). Using clustering and classification techniques, students were grouped into engagement profiles and assigned optimized learning paths.

---

## Files Included

### Notebooks
- `DataPreprocessing.ipynb` – Merges and cleans data from multiple sources
- `ExploratoryDataAnalysis.ipynb` – Visualizes patterns, trends, and distributions
- `Clustering.ipynb` – Uses KMeans to identify engagement profile groups
- `CurriculumOptimization.ipynb` – Assigns tailored curriculum sequences
- `Classification.ipynb` – Optional: Predicts engagement profile based on features

### Data
- `student_mat_por_clean.csv` – Cleaned academic performance dataset (merged)
- `student_mental_health_clean.csv` – Cleaned mental health survey dataset
- `assessments_clean.csv` – Cleaned assessments dataset (Open University)
- `courses_clean.csv` – Cleaned courses metadata
- `vle_clean.csv` – Cleaned Virtual Learning Environment interaction data
- `engagement_profile_sample.csv` – Sample of final dataset (used for modeling)

> 🔎 Note: The full cleaned dataset (`engagement_profile_clean.csv`) is not included due to GitHub size limits. A sample is provided.

---

## Objective

- Create behavioral profiles of students based on online learning data
- Assign curriculum sequences designed to support different engagement levels
- Build a flexible framework that could be applied to neurodivergent learners in future research

---

## Methods Used
- KMeans Clustering (engagement profiles)
- Rule-based Curriculum Mapping
- Optional: Classification using Random Forest
- Exploratory Data Visualizations

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/carlycarroll25/PersonalizedLearning_NeurodivergentStudents.git
   cd PersonalizedLearning_NeurodivergentStudents
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks in order:
   - `DataPreprocessing.ipynb`
   - `ExploratoryDataAnalysis.ipynb`
   - `Clustering.ipynb`
   - `CurriculumOptimization.ipynb`
   - `Classification.ipynb` *(optional)*

---

## 📈 Sample Visualizations

(You can include saved figures here later, such as silhouette plots, cluster distributions, or curriculum flow diagrams.)

---

## Contact

Carly Carroll  
📧 ccarroll1025@gmail.com

---

## Citation

Carroll, C. (2025). *Personalized Learning Models for Neurodivergent Students*. GitHub Repository. https://github.com/carlycarroll25/PersonalizedLearning_NeurodivergentStudents

---

## Future Work
- Apply this framework to datasets with diagnosed neurodivergent learners
- Expand curriculum models with real-time adaptation and reinforcement learning
- Explore longitudinal outcomes for different curriculum pathways
