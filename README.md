# This is the github repo for the R Uni of Manchester & MMU  lead Brexit Data Challenge Hackathon

## Info:

This repository contains R and Python codes used in the analysis for the shortlisted R Uni of Manchester & MMU R User Group submission to the CDRC GISRUK 2018 Brexit Data Challenge (introduced here): https://data.cdrc.ac.uk/dataset/gisruk-data-challenge-2018 and all other codes generated during the Brexit Data Challenge Hackathon.

Additional to the proprietary data provided by CDRC,subsets of tables originally provided by Office of National Statistics (ONS) and www.gov.uk which were linked to the CDRC data are housed here for your convenience; 

2016byage.csv- Mid 2016 population estimates by gender, age in years and LSOA (ONS)

nonUKborn.csv- Non UK born residents by LSOA and year (ONS)

nonUK.rdata- Non UK born residents by LA and year (ONS)

LSOA_LA_key.csv- Conversion key pairing LSOA and LA codes (ONS)

PopDensity2016.csv- Population density 2016 by LSOA (ONS)

Please acknowledge these data providers if accessing these files for further analysis.

View our submission here: https://github.com/RUMgroup/brexit_data_challenge/blob/master/RUM%20Brexit%20Submission%20Doc%2008032018.pdf
Thank you to all participants for your dedication and your fantastic outputs!

## Example data preparation/analysis pipeline

"Ages.r" used to process ONS population estimate data to give LA level figures by age bands

"data_join_notes.r" used to aggregate ethnicity data to the LA level to pair with voting data

Calculate migration rates using "migration.r"

"Adding variables from other sources" script used to merge CDRC data with all open source data derived tables

"Adding variables from other sources" script used to aggregate data table to LA level

"Updated regression 10 year data" used to complete and simplify a regression

Compare time window choice via regression and heatmap comparison using "brellenge_prep.py" and with ANOVA using "check_bw_3_rates.R"

Visualise voting by recent change in white british proportion of population using "line_plot.R"

Map voting by geography using "mapping.R"


## Code of conduct

Our organisations are vectors of the R consortium and adhere to the R Consortium and R Community Code of conduct

### R Community Code of Conduct
A member of the R Community is:

**Open:** Members of the community are open to collaboration, whether it's on projects, working groups, packages, problems, or otherwise. We're receptive to constructive comment and criticism, as the experiences and skill sets of other members contribute to the whole of our efforts. We're accepting of anyone who wishes to take part in our activities, fostering an environment where all can participate and everyone can make a difference.

**Considerate:** Members of the community are considerate of their peers — other R users. We're thoughtful when addressing the efforts of others, keeping in mind that oftentimes the labor was completed simply for the good of the community. We're attentive in our communications, whether in person or online, and we're tactful when approaching differing views.

**Respectful:** Members of the community are respectful. We're respectful of others, their positions, their skills, their commitments, and their efforts. We're respectful of the volunteer efforts that permeate the R community. We're respectful of the processes set forth in the community, and we work within them. When we disagree, we are courteous in raising our issues.

Overall, we're good to each other. We contribute to this community not because we have to, but because we want to. If we remember that, these guidelines will come naturally.
