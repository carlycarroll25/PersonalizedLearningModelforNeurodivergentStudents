# Personalized Learning Models for Neurodivergent Students

This project explores the use of machine learning to create personalized curriculum sequences for students based on their engagement patterns. The goal is to support adaptive learning approaches that can potentially benefit neurodivergent learners, such as those with ADHD or autism, by analyzing behavioral indicators and tailoring learning pathways accordingly.

---

## Project Structure

```
├── notebooks/
│   ├── exploratory_analysis.ipynb
│   ├── clustering_profiles.ipynb
│   ├── curriculum_assignment.ipynb
│   └── create_engagement_profile_sample.ipynb
├── data/
│   ├── engagement_profile_sample.csv
├── figures/
│   └── (graphs, outputs used in report)
├── report/
│   └── final_paper.pdf
├── README.md
└── requirements.txt
```

---

## Dataset

### Included
- `engagement_profile_sample.csv`: A 1,000-row sample of the cleaned dataset used in this project.

### Not Included
The full cleaned dataset `engagement_profile_clean.csv` exceeds GitHub’s file size limit and is not included in the repository.  
To reproduce it:
1. Download the raw data from [Open University Learning Analytics Dataset](https://analyse.kmi.open.ac.uk/open_dataset).
2. Run your own preprocessing steps or request the full cleaned file if needed for academic replication.

---

## Methods

- Behavioral clustering based on engagement metrics (e.g., click counts, credit loads)
- Curriculum assignment based on cluster type (e.g., "High Clicker", "Low Clicker")
- Exploratory analysis and visualization
- Mapping engagement types to structured curriculum paths

---

## How to Run

1. Clone this repository.
2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run notebooks in order:
   - `exploratory_analysis.ipynb`
   - `clustering_profiles.ipynb`
   - `curriculum_assignment.ipynb`

> You can also regenerate the sample dataset using `create_engagement_profile_sample.ipynb`.

---

## Sample Output

- Clustering visualizations
- Curriculum sequence assignments
- Insights into behavioral engagement patterns

---

## Citation

If using or referencing this project in academic work, please cite as:

> Carroll, C. (2025). *Personalized Learning Models for Neurodivergent Students*. GitHub Repository. https://github.com/YOUR_USERNAME/YOUR_REPO

---

## Contact

For questions, academic collaboration, or data access requests:  
**Carly Carroll**  
📧 ccarroll1025@gmail.com
