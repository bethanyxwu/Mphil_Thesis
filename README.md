# Data Cleaning: Exploring Corporate Technology and Innovation Strategy: The Influence of STEM-PhD CTOs

This file contains the data cleaning steps for my thesis "Exploring Corporate Technology and Innovation Strategy: The Influence of STEM-PhD CTOs."

The file includes the following steps:

1. **Cleaning USPTO Patent Assignment Database**:  
   The goal of this step is to extract Patent transactions in the Market for Technology (range 0.0-0.8). The data cleaning process follows the methodology outlined in:  
   **Arora, A., Belenzon, S., & Suh, J. (2022). Science and the market for technology. Management Science, 68(10), 7176-7201.**

2. **Name Matching Assignor and Assignee to Compustat Database**:  
   This step involves using Name matching techniques to link the Assignor (patent transferor) and Assignee (patent assignee) in the USPTO database to corresponding companies in the Compustat database. Additionally, patents are aggregated based on company names in Compustat.

3. **Merging Compustat with BoardEx Data and Aggregated Patent Transaction Counts**:  
   Using the Compustat dataset as the primary data source, BoardEx (which includes CTO information) is merged with it. The aggregated patent transaction counts from Step 2 are also incorporated. This results in a comprehensive firm-year level dataset, ready for regression analysis.
