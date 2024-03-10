## Spot-DataAnalysis

**preprocessing.ipynb** reads raw data, which can be downloaded from OSF, and generates "data" folder. In preprocessing, unrelevant timestamps are deleted and the coordinates of the measurements are calibrated.  
"newdata" folder was generated as the middle step in preprocessing, but not used in the final analysis. 

**trajectory_analysis.ipynb** perform analysis and generates plots used in the paper, reading data in the "data" folder. **helpers.py** needs to be in the same directory with the **trajectory_analysis.ipynb**

**questionnaire_analysis.ipynb** was used to analize the questionnaires. 


