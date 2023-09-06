## Spot-DataAnalysis

**preprocessing.ipynb** reads raw data, which is to be downloaded from OSF and extracts files for each trial. **newdata** folder and **traj_data** folder are generated from this script. The difference between the two is: **newdata** is simply raw data without unrelevant timestamps. In **traj_data**, the coordinate is transformed so that Spot and human move along the x-axis. 

**Spot_trajectory_analysis.ipynb** reads "newdata" or "traj_data" to do analysis. 

**helpers.py** needs to be in the same directory with the **Spot_trajectory_analysis.ipynb**
