# Using Animal Control Incident Data to Improve Animal Welfare by Community
## DSC 680 - Applied Data Science - Project 1

### Abstract
According to research estimates from the American Society for the Prevention of Cruelty to Animals (ASPCA), over 6.5 million animals enter shelters each year [7]. Of those, approximately 1.5 million animals are euthanized [7]. Animals of all species and breeds enter shelters in multiple ways. They can be surrendered by their former owners, rescued by individuals or authorities as strays, or confiscated from a cruelty case. [9] Most municipalities have an animal control or humane law entity that is responsible for responding to animal complaints and emergencies.  Sometimes these agencies are publicly funded, and sometimes they are part of a private nonprofit animal welfare organization. [10] Animal control officers sometimes have a bad reputation, but often their desire is to maintain the best quality of life for animals in the community. Common problems that they work towards improving include pet overpopulation, cruelty and dogfighting, and feral cat community control.  The objective of this project was to analyze animal control incident data collected by an animal control agency and use it to provide vital information to address animal welfare problems.  

Overall, we can say that yes, this data can be helpful in directing locations for additional animal welfare support programs.  In each of the problems we assessed, pet overpopulation, dog fighting, and feral cat control, most incidents were centered around the city of Baton Rouge with a large number just south of the Industrial Complex. Additional patrols can be set up in this area to determine why these problems are so prevalent there.  Before introducing new programs into the area, further analysis should be completed on the specific neighborhoods within the city of Baton Rouge to isolate any clusters. The predictive models were effective at predicting conditions and temperaments that would be most beneficial to know before an animal control officer arrives on the scene.  This model could be used as part of an alert system within the animal control dispatch software to notify them that initial support is needed. The model should be tested further on unseen data to further evaluate its effectiveness.

### Contents
Root
- Project Proposal - LewisRebecca_Project1_Proposal.pdf
- Data Visualizations - LewisRebecca_DataVisualizations.twb
- Final Paper - LewisRebecca_Project1_Paper_FINAL.pdf
- Final Slides - LewisRebecca_Project1_Presentation_.pptx
- For a recorded presentation in mp4 format, please contact me at revlewis79@gmail.com.

Data
- BR_Animal_Control_Calls.csv
- RAW_Animal_Control_Incidents.csv

Scripts
- Condition_Classification_Model.ipynb
- Data_Preparation.ipynb
- Data_Profling.ipynb
- Feature_Engineering.ipynb
- Temperament_Classification_Model.ipynb

### Requirements
Jupyter Notebook
Packages include pandas, numpy, pycaret, pandas-profiling, datetime

### Usage
1. Download the files in the same folder structure.
2. Run the scripts in the following order:
    1. Data_Preparation.ipynb
    2. Data_Profiling.ipynb
    3. Feature_Engineering.ipynb
    4. Condition_Classification_Model.ipynb
    5. Temperament_Classification_Model.ipynb










