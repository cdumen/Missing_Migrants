
## Data Science Blog Post - Missing Migrants

### Table of Contents
1. [Installation](#Installation)
2. [Project Motivation](#Project_Motivation)
3. [File Description](#File_Description)
4. [Results](#Results)
5. [Licencing, Authors, and Acknowledgements](#Licencing_Authors_and_Acknowledgements)

### Installation

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

You will need to download Kaggle's Missing Migrants data and put in the same folder with Notebook .ipynb folders. You can find the data to download [here](https://www.kaggle.com/snocco/missing-migrants-project).

### Project Motivation

For this project, I was interestested in using Kaggle's Missing Migrants Dataset to better understand:

1. Distribution of total dead and missing number of migrants among the years to understand the conditions.
2. Region of Incident to understand the route and road conditions
3. Top causes of death to investigate the migrants death reasoning.

### File Description

There are 1 notebooks available here to showcase work related to the above questions. The notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title. Markdown cells & comments were used to assist in walking through the thought process for individual steps.

Missing Migrants Project tracks deaths of migrants, including refugees and asylum-seekers, who have gone missing along mixed migration routes worldwide. The dataset columns are:

* **Web ID**: An automatically generated number used to identify each unique entry in the dataset.
* **Region of Incident**: The region in which an incident took place. For more about regional classifications used in the dataset, click [here](https://missingmigrants.iom.int/regional-classifications).
* **The reported date of incident**: Estimated date of death. In cases where the exact date of death is not known, this variable indicates the date in which the body or bodies were found. In cases where data are drawn from surviving migrants, witnesses or other interviews, this variable is entered as the date of the death as reported by the interviewee.  At a minimum, the month and the year of death is recorded. In some cases, official statistics are not disaggregated by the incident, meaning that data is reported as a total number of deaths occurring during a certain time period. In such cases the entry is marked as a “cumulative total,” and the latest date of the range is recorded, with the full dates recorded in the comments.
* **Reported Year**: The year in which the incident occurred.
* **Reported Month**: The month in which the incident occurred.
* **Total Dead Migrants**: The total number of people confirmed dead in one incident, i.e. the number of bodies recovered.  If migrants are missing and presumed dead, such as in cases of shipwrecks, leave blank
* **Minimum Estimated Number of Missing**: The total number of those who are missing and are thus assumed to be dead.  This variable is generally recorded in incidents involving shipwrecks.  The number of missing is calculated by subtracting the number of bodies recovered from a shipwreck and the number of survivors from the total number of migrants reported to have been on the boat.  This number may be reported by surviving migrants or witnesses.  If no missing persons are reported, it is left blank.
* **Total Dead and Missing Migrants**: The sum of the ‘number dead’ and ‘number missing’ variables.
* **Number of Survivors**: The number of migrants that survived the incident, if known. The age, gender, and country of origin of survivors are recorded in the ‘Comments’ variable if known. If unknown, it is left blank
* **Number of Females**: Indicates the number of females found dead or missing. If unknown, it is left blank.
* **Number of Males**: Indicates the number of males found dead or missing. If unknown, it is left blank.
* **Number of Children**: Indicates the number of individuals under the age of 18 found dead or missing. If unknown, it is left blank.
* **Cause of Death**: The determination of conditions resulting in the migrant's death i.e. the circumstances of the event that produced the fatal injury. If unknown, the reason why is included where possible.  For example, “Unknown – skeletal remains only”, is used in cases in which only the skeleton of the decedent was found.
* **Location Description**: Place where the death(s) occurred or where the body or bodies were found. Nearby towns or cities or borders are included where possible. When incidents are reported in an unspecified location, this will be noted
* **Information Source**: Information provided by whom/where
* **Location Coordinates**: Place where the death(s) occurred or where the body or bodies were found. In many regions, most notably the Mediterranean, geographic coordinates are estimated as precise locations are not often known. The location description should always be checked against the location coordinates.
* **Migration Route**: Name of the migrant route on which incident occurred, if known. If unknown, it is left blank.
* **Url Sites for Info**: 
* **UNSD Geographical Grouping**: Geographical region in which the incident took place, as designated by the United Nations Statistics Division (UNSD) geoscheme. For more about regional classifications used in the dataset, click [here](https://unstats.un.org/unsd/methodology/m49/).
* **Source Quality**: Incidents are ranked on a scale from 1-5 based on the source(s) of information available. Incidents ranked as level 1 are based on information from only one media source. Incidents ranked as level 2 are based on information from uncorroborated eyewitness accounts or data from survey respondents. Incidents ranked as level 3 are based on information from multiple media reports, while level 4 incidents are based on information from at least one NGO, IGO, or another humanitarian actor with direct knowledge of the incident. Incidents ranked at level 5 are based on information from official sources such as coroners, medical examiners, or government officials OR from multiple humanitarian actors.




### Results

The main findings of the code can be found at the post available [here](https://medium.com/@cerendumen/investigating-missing-migrants-9823a0423e94).

### Licencing, Authors, and Acknowledgements

Must give credit to Stefano Nocco & Kaggle for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/snocco/missing-migrants-project). Otherwise, feel free to use the code here as you would like!
