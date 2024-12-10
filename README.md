# Drug Similarity Analysis
## Project Overview
This repository contains reports and workflow for identifying drugs structurally similar to market viable ones for the treatment of various diseases. We choose drugs that already exist for the treatment of the aforesaid disease and compare drug similarity by using various drug libraries/working mechanisms.
## Workflow and Tools
- **Data Source** : PubChem Database
- **Tools Used** : KNIME for computational analysis, leveraging nodes for feature extraction, similarity scoring, and visuzalization.
- **Analysis Methods** :
   - **2D similarity** : Tanimoto Coefficients
   - **3D Similarity** : Root mean square deviation (RMSD)
## Key Steps
1. **Data pre-processing** :
- Molecule retrieval from PubChem.
- Conversion to standard format (e.g: SMILES, SDF).
- Structural normalization.
    
2. **Feature extraction** : Calculation of 2D and 3D molecular descriptors
3. **Similarity analysis** : Scoring based on Tanimoto (2D) and RMSD (3D).
4. **Visualization** : Scatter plots and heatmaps for interpretability.
5. **Filtering** : Shortlisting compounds with high similarity scores.
- 5.1.**Rows**: Represent individual molecules from the dataset. Each row corresponds to one compound from drug library.
- 5.2.**Columns**:
  - **RMSD**: shows the Root Mean Square Deviation (RMSD) values for the alignment of the drug library.
  - **Score**: Represents the alignment or similarity scores.  
- Yellow: Indicates lower scores or RMSD values.
- Blue: Indicates higher scores or RMSD values.
  
## Results
- **Yellow** : Indicates low similarity in heatmap
- **Blue** : Indicates high similarity in heatmap
  
## Conclusion
This project simply demonstrates the power of computational tools in identifying structurally similar drugs. By combining 2D fingerprint analysis with 3D spatial alignment, a well-rounded approach to molecular similarity evaluation can be acheived. The findings provide insights into potential drug alternatives for various diseases and pave the way for further research in drug discovery.

## Acknowledgment
- **@Bversity School of Bioscience**
- **@Bversity+ Community**
