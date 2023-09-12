# mammology-data-analysis
The FDA has received an international grant to provide mammography equipment and training to currently uncertified medical facilities nationwide. Analyze the characteristics of already certified facilities and state populations to determine gaps in current mammography coverage in order to help the FDA allocate their funds.

Two datasets were given to us: 
One containing information on all currently certified mammography facilities in the United States.
The 2019 Census Dataset which contains information regarding the age and sex compositions of state populations in the United States from 2010-2019

Our project essentially takes data from the U.S census, and breast cancer facilities across the nation, in order to determine where to best allocate future funds to bolster the ability to get mammograms across the country.
We built it using python and the pandas library, along with many other to parse through, and analyze the data.

Cleaned both datasets, “beginner.csv” and “sc-est2019-agesex-civ.csv” to give us the information we need: the amount of licensed medical facilities that can perform mammograms per state and the population information on women over 40 in each state across the United States

Why women over 40? - Only about 7% of women with breast cancer are under 40, so we narrowed the scope of our analysis to women over 40, as breast cancer is much more common. (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2894028/)

