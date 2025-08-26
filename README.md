# 🏟️ Data Analysis on US Sports Data (NBA, NHL, NFL, MLB)

This project explores how to **automate the ingestion, cleaning, and standardization of messy sports datasets** across major US leagues (NBA, MLB, NHL, NFL) in compliance to official census metro-area data.  
The question we explore in this EDA project is: **Do bigger cities perform better in professional sports?**

In exploration of this question we compute the Pearson correlation of each metro-area with the aggregated W/L% ratio of the teams that it contains. 
Moreover, in order to reduce the amount of manual mappings of 100+ teams to their region, we developed a heuristic based technique (first token of string + some manual overiding) that handled about 80% of the matches reducing the time of mapping by hours. 

---

## 🔑 Highlights

- **Unified Pipeline:** Built a reusable cleaning + standardization pipeline to handle different league datasets.  
- **Automated Name Mapping:** Developed a hybrid heuristic (first-token + manual overrides) that auto-resolved ~80 team–city matches, eliminating hours of manual reconciliation across 100+ potential mappings.  
- **Statistical Rigor:** Computed Pearson correlation between metro population and team performance (W/L%), aggregated by city.  
- **Scalability:** Extended from NBA to MLB, NHL, and NFL with minimal additional code.  

---

## 📊 Findings

Each league’s correlation analysis is available in the corresponding notebook.  

**Consensus:** 🏆 Talent exists everywhere.  


