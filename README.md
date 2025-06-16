# 2023 OBS Summary

Locate at: [notebooks/2023_Summary](https://github.com/SANDAG/Summary_OBS/tree/2023-summary/notebooks/2023_Summary).

The entire set of scripts (00–03, four scripts in total) processes three main inputs: the original survey data, the reweighted survey trips, and a TAZ-to-district lookup table. The primary goal is to create additional columns that support summarizing and analyzing the survey data. These include trip purpose in Production-Attraction (PA) format, mode of access in PA format, and rider information. The output is a more detailed and comprehensive dataset suitable for further analysis.

In addition, the scripts generate high-level summary tables that support the final report. Look for sections labeled `Table xx in Report` to see how each output corresponds to the Mid-Coast After Study Report.


### Structure

- **High-Level Summary**
  - Define Trip Purpose, Auto Ownership, and Mode of Access
  - Project Trips Summary  
    - *Table 3 in Report*

- **Station Boardings and Alightings**
  - *Tables 7, 8, and 21 in Report*

- **District-to-District Summary**
  - *Table 6 and Appendix A in Report*

- **Station Portfolio Analysis** *(Section 2.1.2.1 in Report)*
  - Generates final full datasets
  - Reference: `4_2_Rider_Portfolio_by_Station_Archive.xlsx` for the Report
  

### Environments
pandas==2.2.3

numpy==2.2.5
