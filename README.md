![CarpPlanner Banner](./_pictures_/_CarpPlannerBanner_.png)
# CarpPlanner
This is the README for the CarpPlanner program for processing and analyzing datasets from husbandry of carp. CarpPlanner can be used to filter and analyze data generated during the spawning, husbandry, and experimentation on individually labeled carp. 

# How to use
Download the repository contents or clone locally using Git.
The main script is included as a Jupyter Notebook. The authors suggest running in Jupyter. https://jupyter.org/
Open the working directory. Below is the file tree.

├───CarpPlanner
│   CarpPlanner Banner.png
│   CarpPlanner Codebook draft2.docx
│   CarpPlanner.ipynb
│   README.md
│
├───Example_Output
│       2025-11-16_226001512607_handling_logs.xlsx
│       2025-11-16_226001512608_handling_logs.xlsx
│       2025-11-16_226001512614_handling_logs.xlsx
│       2025-11-16_226001512619_handling_logs.xlsx
│       2025-11-16_226001512635_handling_logs.xlsx
│       2025-11-16_226001512643_handling_logs.xlsx
│       2025-11-16_226001512651_handling_logs.xlsx
│       2025-11-16_226001512661_handling_logs.xlsx
│       2025-11-16_226001512680_handling_logs.xlsx
│       2025-11-16_226001512689_handling_logs.xlsx
│       2025-11-16_fish_roster.xlsx
│       2025-11-16_handling_logs.xlsx
│       2025-11-16_tank_status.xlsx
│
├───Fish_Handling_Logs
│       2019 Carp Handling Log.xlsx
│       2020 Carp Handling Log.xlsx
│       2021 Carp Handling Log.xlsx
│       2022 Carp Handling Log.xlsx
│       2023 Carp Handling Log.xlsx
│       2024 Carp Handling Log.xlsx
│       2025 Carp Handling Log.xlsx
│
└───Output_Files

Open CarpPlanner.ipynb. Python code is contained in a sequence of "cells". 
One can run all cells at once by clicking run -> run all cells. Alternatively, one can run cells one-by-one by pressing shift-enter. 
Try running all cells. Check the Output_Files directory. If it is working, the output files should be identical to the files in Example_Output.  

One you show it is working on your computer, you can replace input files in Fish_Handling_Logs to process your own records.

# Dependencies
The included Jupyter notebook uses the following Python libraries. Other versions may work. If errors arise due to dependencies, consider using a virtual environment to ensure all the correct versions are being used.
Python: 3.11.7
pandas: 2.1.4
numpy: 1.26.4
matplotlib: 3.8.0
seaborn: 0.12.2
# Reporting Bugs
Report any bugs to Julie Badger (beenk006@umn.edu). 
When reporting bugs, please include the any output printed in the Jupyter, as well as any output files saved when running the pipeline.
# Citation
TBD
