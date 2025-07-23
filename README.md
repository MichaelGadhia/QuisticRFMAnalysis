# RFM Segmentation for Subscriber Re-Engagement

## Project Summary
This project applies RFM (Recency, Frequency, Monetary) clustering to segment over 50,000 Quistic email subscribers based on engagement behavior. The goal was to identify dormant but high-value users for targeted re-engagement and to improve overall list health through strategic pruning. The resulting campaign changes led to a measurable increase in clickthrough rates.

## Objectives
- Segment subscribers by behavioral patterns using RFM methodology
- Identify high-value users with declining engagement
- Enable targeted re-engagement campaigns and list hygiene strategies
- Measure the impact of these actions on clickthrough rate (CTR)

## Data
- Source: Internal email engagement data from Quistic campaigns
- Scope: 50,000+ subscribers
- Features included:
  - Last engagement timestamp (Recency)
  - Number of opens/clicks over past 180 days (Frequency)
  - Revenue (Monetary)
 
## Methods
- Data cleaning and feature engineering with pandas
- RFM score generation (all dimensions normalized)
- K-Means clustering with scikit-learn
- Cluster evaluation using silhouette score
- Cluster visualization (2D and 3D plots with matplotlib / seaborn)
- Interpretation of segments for business actionability

## Key Segments Identified
- Loyal Engagers: High frequency + recent + purchases
- Dormant Buyers: Low recency, but past purchase activity
- Cold Leads: Low across all RFM dimensions

## Actions Taken
- Custom re-engagement campaigns for “Dormant Buyers”
- Removal or suppression of low-engagement, non-paying users
- Adjustments to email frequency and content personalization

## Results
- CTR increase: +15% 
- Improved email deliverability and engagement consistency
- Created an internal playbook for ongoing segmentation strategy

## Tools Used
- Python (pandas, scikit-learn, matplotlib, seaborn)
- Jupyter Notebooks

## Files Included
- `rfm_segmentation.ipynb` – data cleaning, scoring, clustering
- `cluster_analysis.png` – visuals of key segment distributions colored by cluster
- `2D_plots.png` – pairwise plots of RFM features colored by cluster
- `rfm_segmentation_readout.pdf` – full visual of processing and analysis viewable by CEO
- `README.md` – this document

\
**Michael Gadhia**\
Data Analyst | Boston, MA\
michaelmgadhia@proton.me
