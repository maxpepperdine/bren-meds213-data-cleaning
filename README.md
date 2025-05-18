# Cleaning the shorebird survey data 


## The data set

ARCTIC SHOREBIRD DEMOGRAPHICS NETWORK [https://doi.org/10.18739/A2222R68W](https://doi.org/10.18739/A2222R68W)

Data set hosted by the [NSF Arctic Data Center](https://arcticdata.io) data repository 

Field data on shorebird ecology and environmental conditions were collected from 1993-2014 at 16 field sites in Alaska, Canada, and Russia.

![Shorebird, copyright NYT](https://static01.nyt.com/images/2017/09/10/nyregion/10NATURE1/10NATURE1-superJumbo.jpg?quality=75&auto=webp)

Data were not collected every year at all sites. Studies of the population ecology of these birds included nest-monitoring to determine the timing of reproduction and reproductive success; live capture of birds to collect blood samples, feathers, and fecal samples for investigations of population structure and pathogens; banding of birds to determine annual survival rates; resighting of color-banded birds to determine space use and site fidelity; and use of light-sensitive geolocators to investigate migratory movements. 

Data on climatic conditions, prey abundance, and predators were also collected. Environmental data included weather stations that recorded daily climatic conditions, surveys of seasonal snowmelt, weekly sampling of terrestrial and aquatic invertebrates that are prey of shorebirds, live trapping of small mammals (alternate prey for shorebird predators), and daily counts of potential predators (jaegers, falcons, foxes). Detailed field methods for each year are available in the `ASDN_protocol_201X.pdf` files. All research was conducted under permits from relevant federal, state, and university authorities.

See `01_ASDN_Readme.txt` provided in the [course data repository](https://github.com/UCSB-Library-Research-Data-Services/bren-meds213-spring-2024-class-data) for full metadata information about this data set.

# Metadata for the cleaned snow survey data (week 7 metadata assignment)

## DATA & FILE OVERVIEW

#### (1) File list contained in the dataset

The raw `snow survey` data (`data/raw/ASDN_Snow_survey.csv`) was downloaded and cleaned in R in the `eds213_data_cleaning_assign_Maxwell_Pepperdine.qmd` script, and the cleaned data was saved as a CSV file in this repository (`data/processed/all_cover_fixed_Maxwell_Peperdine.csv`). 

**QUESTION**

#### (2) Relationship between files

Not important for this file. 

**QUESTION**

#### (3) Additionl related data collected not included in the current data package

There are no additional related data collected that were not included in the current data package.

**QUESTION**

#### (4) Are there multiple versions of the dataset?

There are two versions of the `snow survey` dataset, one raw and one cleaned version. The data were cleaned in the `eds213_data_cleaning_assign_Maxwell_Pepperdine.qmd` script. The raw data (`data/raw/ASDN_Snow_survey.csv`) was downloaded and cleaned in R, and the cleaned data was saved as a CSV file in this repository (`data/processed/all_cover_fixed_Maxwell_Peperdine.csv`). 

**QUESTION**

## DATA SPECIFIC INFORMATION FOR: 

For the file: `data/processed/all_cover_fixed_Maxwell_Peperdine.csv`

#### (1) Number of variables: `11`

#### (2) Number of cases/rows: `42831`

#### (3) Variable list and description

The cleaned data file contains the following columns/variables:

```
├── Site          # Four-letter code of site at which data were collected
├── Year          # Year in which data were collected      
├── Date          # Date on which data were collected (DD-MM-YY)                   
├── Plot          # Name of study plot on which survey was conducted
├── Location      # Name of dedicated snow-survey location (if applicable)
├── Snow_cover    # Percent cover of snow, including slush (%)
├── Water_cover   # Percent cover of water (%)
├── Land_cover    # Percent cover of exposed land (%)
├── Total_cover   # Total sum of cover types (to check the above, should sum to 100) (%)
├── Observer      # Person who conducted the survey
├── Notes         # Any relevant comments on the survey
```

#### (4) Missing data codes 

In the `data/processed/all_cover_fixed_Maxwell_Peperdine.csv` file, missing data are identified with `NA` values. We converted the following code/symbols in the raw data (`data/raw/ASDN_Snow_survey.csv`) to `NA` values in the cleaned data (`data/processed/all_cover_fixed_Maxwell_Peperdine.csv`) file:

- `.`
- `-`
- `n/a`
- `unk`
- `<0` values
- `<row r=\\64\\ spans=\\1:11\\ x14ac:dyDescent=\\0.2\\>`

#### (5) Specialized formats or other abbreviations used

This file contains no other specialized formats or abbreviations.

## SHARING/ACCESS INFORMATION

#### (1) Licenses/restrictions placed on the data:

There are no restrictions on the data. The data are publicly available and can be used for any purpose, including commercial use, as long as the original source is cited.

#### (2) Links to publications that cite or use the data:

- [Lanctot et al., 2015](https://bksandercock.wordpress.com/wp-content/uploads/2018/10/lanctot2015asdnreport.pdf)
- [Weiser et al., 2017](https://doi.org/10.1111/ibi.12571)
- [Weiser et al., 2017](https://doi.org/10.1642/AUK-17-107.1)

#### (3) Links to other publicly accessible locations of the data:

ARCTIC SHOREBIRD DEMOGRAPHICS NETWORK [https://doi.org/10.18739/A2222R68W](https://doi.org/10.18739/A2222R68W)

Data set hosted by the [NSF Arctic Data Center](https://arcticdata.io) data repository

#### (4) Links/relationships to ancillary data sets 

The [Arctic Shorebird Demographics Network](https://arcticdata.io/catalog/view/doi%3A10.18739%2FA2CD5M) has various other data sets available that include information on shorebird ecology and environmental conditions between 1993-2014 at 16 field sites in Alaska, Canada, and Russia. Data were not collected every year at all sites. Studies of the population ecology of these birds included nest-monitoring to determine the timing of reproduction and reproductive success; live capture of birds to collect blood samples, feathers, and fecal samples for investigations of population structure and pathogens; banding of birds to determine annual survival rates; resighting of color-banded birds to determine space use and site fidelity; and use of light-sensitive geolocators to investigate migratory movements.

See the link above for more information on the data sets available, and the `data/raw/01_ASDN_Readme.txt` file provided in the course data repository for full metadata information about all data sets.

#### (5) Was data derived from another source?

The data were collected by the Arctic Shorebird Demographics Network (ASDN) and are hosted by the NSF Arctic Data Center. 

#### (6) Recommended data citation:

Lanctot, R. B., Brown, S., & Sandercock, B. K. (2017). Arctic Shorebird Demographics Network. (<https://doi.org/10.18739/A2CD5M>).










































