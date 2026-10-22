# Zillow-Rent-Data-Quality-Audit
Python-based data curation and quality audit workflow for Zillow Observed Rent Index (ZORI) data, including profiling, completeness analysis, consistency checks, equity assessment, and governance documentation.

## **Overview**  
This pilot demonstrates a full data‑curation workflow using the **Zillow Observed Rent Index (ZORI)** dataset. The goal is to evaluate rental‑market data quality, document curation decisions, and produce a reproducible workflow that aligns with academic requirements for appraisal, ingest, processing, preservation, access, reuse, and responsible data practice.

### **How to Run the Code**

1. **Clone the repository**  
   ```bash
   git clone <your-repo-url>
   cd <repo-name>
   ```

2. **Install dependencies**  
   The pilot uses standard Python data‑analysis libraries.  
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Jupyter notebook**  
   ```bash
   jupyter notebook Quality_Audit.ipynb
   ```

4. **Run the notebook cells in order**  
   The workflow is sequential:
   - Load raw ZORI dataset  
   - Profile dataset structure  
   - Run completeness, accuracy, consistency, timeliness checks  
   - Generate audit summaries  
   - Document findings  

5. **Raw vs. processed data**  
   - `data/raw/` contains the untouched Zillow download  
   - `data/working/` contains the cleaned working copy used for the pilot  
   - All transformations are logged inside the notebook for reproducibility  

---
