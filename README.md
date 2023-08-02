
# Data Visualization Project

Description..


# Data sets


We currently have two datasets from CJST and EJScreen Info. EJScreen uses 2020 Census tracts (and IDs) while CEJST still uses 2010. 

The raw and processed data are stored in this  [GDrive](https://drive.google.com/drive/folders/1DW8KQmTR1pHRw7dMYcizVAe9a-mCl3zr) shared in this folder in zip and it should be uncompressed to use. Since, the data is large unable to use git's [Large File Storage](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github) is over its data quota.



## Community Burden Identification Tool

This tool aims to identify communities that are marginalized, underserved, and overburdened by pollution. These communities are located in census tracts that meet or exceed the thresholds in one or more of eight categories of criteria.

## Definition of Disadvantaged Community:
A community is considered disadvantaged if it exhibits one or more of the eight categories of burden and also falls under the low-income category.

Eight Categories of Burden:

- Climate Change
- Energy
- Health
- Housing
- Legacy Pollution
- Transportation
- Water & Wastewater
- Workforce Development

## Low Income Criteria:
A census tract is categorized as low income if it meets or exceeds the 65th percentile for low income, as defined by households at or below 200% of the Federal poverty level.

## Data and Geography:
The tool utilizes census tracts, representing approximately 4,000 people, as the smallest unit of geography for which consistent data can be displayed.

Please refer to the documentation and code for further details and implementation instructions.

#### Steps 

1. Visit https://screeningtool.geoplatform.gov/

2. Go to your location of interest by entering the address or Zip code. You can also zoom into your region.

![Capture](https://github.com/sci4ga/ej_tools_and_data_exploration/assets/133727441/1918eb82-21b5-49ae-a2a2-613000b306e5)

3. Evaluate census tracts and what qualifies communities as disadvantage.
![Step 3](https://github.com/sci4ga/ej_tools_and_data_exploration/assets/133727441/dbf847aa-c550-413c-a66e-0c72dca20ba8)


## Deployment

1. Clone the repository:

2. Make sure to download all shapefiles (shp files) from the drive and place them in the same directory before proceeding with the next steps.

3. Install dependencies:
```bash
  pip install -r requirements.txt
```
