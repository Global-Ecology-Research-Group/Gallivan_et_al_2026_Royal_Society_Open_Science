This repository contains all the code and files used in the analyses reported in "iNaturalist and EDDMapS provide complementary data for monitoring non-native herpetofauna in Florida" article, which is published in Royal Society of Open Science

# Code Folder

This folder contains all R scripts which can be used to repeat the results presented in the article and supplemental material.

**Get_source_for_species_status –** Script to define species as native or non-native using multiple sources and downloading data for species distribution from the Reptile Database.

**Clean Code** - Main script used in the conduction of the manuscript comparing non-native herpetofauna across EDDMapS and iNaturalist. This script contains all data curation, main analyses, and figure generation. This code is organized to follow our manuscripts 3 main Objectives

# Data

This folder contains all data used in the analyses. The following is a description of data present in this repository:

**AmphiBIO_v1.csv** - Table containing all trait data for Amphibian species used within this study across Florida.

**eddmaps_introduced.csv** - Table containing a list of all introduced Reptile and Amphibian species observed via EDDMapS within Florida.

**EDDMapS_observations.csv** - Table containing all raw EDDMapS observations for all introduced Reptile and Amphibian individuals across Florida.

**iNat_herp_data.RDS** - RDS file that contains all raw iNaturalist herpetofauna observations across Florida.

**iNaturalist_introduced.csv** - Table containing a list of all introduced Reptile and Amphibian species observed via iNaturalist.

**native_nonative_status –** This folder contains source data to define species as native or non-native, as well as our final designations.

-   **floridamuseum_speciesstatus:** Table of native and introduced status of florida reptiles and amphibians from the Florida Museum ([https://www.floridamuseum.ufl.edu/discover-herps/florida-amphibians-reptiles](https://www.floridamuseum.ufl.edu/discover-herps/florida-amphibians-reptiles/){.uri}).

-   **Kyrsko_et_al_2016:** Table of non-native and introduced species manually extracted from Krysko et al. (2016): <https://doi.org/10.17161/randa.v23i2.14119>

-   **referenced_source_list_for_species_status:** Final native/non-native designation for each reptile and amphibian species found in iNaturalist and EDDMapS and the source used to determine this designation.

-   **Reptile_Database_Distribution:** The distribution of reptile species not found in other available datasets from The Reptile Database (<http://www.reptile-database.org/>).

**RepTrait dataset V1-2_data.csv** - Table containing all trait data for Reptile species used in this study across Florida.

# Figures

This folder contains all the figures presented in the paper. A sub-folder named "Supplemental" contains all the supplemental figures.
