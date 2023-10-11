# Brazil Conflict Tracker (2018-2023) Data Analysis

## Overview
This repository contains the final project for the Statistics course in the Data Science program at Ada Tech School. The dataset utilized in this project is derived from Kaggle and encompasses various conflict events in Brazil ranging from armed conflicts with fatalities to peaceful protests and marches.

All data used are official figures sourced from the Armed Conflict Location & Event Data Project (ACLED). 

## Insights & Analysis
The notebook within this repository provides comprehensive insights and analysis of the conflict events. For each significant event, further information and interpretations based on the author's understanding and research have been included.

## Getting Started
### Accessing the Notebook
- Navigate to the repository where the project is stored.
- Look for the notebook file with the `.ipynb` extension. You can open and view the notebook directly on GitHub.

### Dataset
- A copy of the dataset used for the analysis in `.csv` format is included in a folder within the repository for easy access.

### Prerequisites
- Ensure you have a Jupyter Notebook environment set up and running to run the notebook on your local machine.
- The necessary libraries and dependencies required to run the notebook are listed within the notebook itself.

## Data Sources Overview
The foundational data for this project is derived from the Armed Conflict Location & Event Data Project (ACLED). ACLED consolidates conflict reports gathered from various levels - local, regional, national, and international - to ensure both the volume and quality of the data are maintained.

### ACLED’s Latin America & Caribbean Regional Dataset
This weekly-updated dataset provided the initial conflict data related to Brazil for our analysis. Significant data cleaning was imperative due to the presence of numerous ID-related variables and missing values.

### ACLED's Codebook (January 2021)
The Codebook from ACLED was invaluable for our project, helping us understand the criteria that define "conflicts" and providing insights into the various ways the data can be leveraged for analysis.

### ACLED’s Data Columns (April 2019)
This document provided the necessary clarifications and definitions for any variables in ACLED’s original Latin America & Caribbean dataset that were unclear or undefined.

## Tracked Statistics
- **EVENT_DATE:** Date of the conflict event.
- **EVENT_TYPE:** General category of the conflict.
- **SUB_EVENT_TYPE:** More specific category or subtype of the conflict.
- **ACTOR1 & ACTOR2:** Named entities involved in the conflict, with ACTOR2 being associated with or identified as ACTOR1.
- **COUNTRY:** Country where the conflict occurred (specifically Brazil in this dataset).
- **LOCATION:** Precise location of the conflict event.
- **LATITUDE & LONGITUDE:** Geographic coordinates of the conflict location.
- **SOURCE_SCALE:** Scale of the data source (local, regional, national, or international).
- **NOTES:** Brief description providing context to the conflict.
- **FATALITIES:** Number of deaths reported in the conflict event.

## Credits
Special acknowledgment to Justin Oh , the Kaggle user responsible for compiling and making this dataset available to the public. 

## Contributing
Due to the extensive number of variables in this database, this analysis project extends to various other necessary nuances for a conclusive data analysis.
If you have suggestions or improvements, feel free to contribute. Ensure your contributions are in line with the project’s guidelines and relevant to the analysis and insights provided.

## License
Be aware of and respect the license attached to the dataset on Kaggle during usage and distribution.

## Acknowledgments
- Thanks to ACLED for providing the original dataset.
- Ada Tech School for their guidance and educational support during the project.
