# 🎬 Action Hotspots: Netflix Content Acquisition Strategy via Clustering

## Project Overview
This project applies **K-Means clustering** and **data analysis** on the Netflix Titles dataset to optimize content acquisition. The goal was to move beyond simple genre analysis and identify distinct audience segments or "hotspots" to maximize return on investment (ROI) for new content.

The analysis led to the identification of key clusters that exhibit strong preferences for specific content types (e.g., Action/Adventure) and geographical origins, providing **actionable business recommendations**.

## Key Findings & Business Recommendations
* **The Action Hotspot:** A dominant cluster was identified showing a clear and strong preference for **Action & Adventure** content, suggesting a key target audience for fast-paced content investment.
* **Geographical Focus:** Analysis of the cluster content (as shown in the presentation) highlighted specific countries/regions with a high concentration of popular Action content, recommending them as prime markets for content localization and acquisition.
* **Strategic Optimization:** Recommendations were developed to help Netflix balance their content spending between established audience segments and high-demand, high-potential new content based on cluster profiles.

## Technical Approach & Methodology
The data analysis pipeline included:

1.  **Data Preprocessing:** Handled missing values (specifically in the `listed_in` column) and prepared categorical features.
2.  **Feature Engineering:** The genre column (`listed_in`) was prepared for numerical analysis using **Label Encoding**.
3.  **Clustering:** The **K-Means algorithm** was applied to group Netflix titles based on shared genre and structural profiles.
4.  **Interpretation:** Visualizations were used to interpret the distinct characteristics of each cluster (e.g., genre dominance and regional patterns).

## Project Files
| File Name | Description |
| :--- | :--- |
| `netflix nlp.ipynb` | The primary **Jupyter Notebook** containing all data cleaning, feature engineering, K-Means clustering logic, and visualization code. |
| `Uncovering Global Action Hotspots netflix saith krishna.pptx` | The **Final Presentation** summarizing the methodology, key findings, and strategic recommendations for the business case. |
| `netflix_titles.csv` | The **raw dataset** used for the analysis. |

## Technologies Used
* Python 3.x
* **Pandas & NumPy** (Data manipulation)
* **Scikit-learn (sklearn)** (Clustering: K-Means; Encoding: LabelEncoder)
* **Matplotlib / Seaborn** (Data visualization)
