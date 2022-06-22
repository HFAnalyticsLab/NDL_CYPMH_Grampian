<img src="ndlbanner.png" width="32%"> <img src="achds logo.jpg" width="32%"> <img src="nhsg-branding.jpg" width="32%">

# Networked Data Lab: NDL Grampian analysis on mental health prescribing and CAMHS referrals

#### Project Status: In-progress

## How does this repository work?

We are unable to share the individual-level data used to conduct this analysis. Although the information is anonymised to avoid disclosure of personal information, there is still a risk of identification. However, in the interests of transparency and reproducibility we are making summary (i.e. aggregate) data available here alongside the script files used to analyse and visualise the data.

## Project Description

- This Networked Data Lab analysis by the NDL lab in Grampian explores community mental health prescribing and specialist Child and Adolescent Mental Health Services (CAMHS) referral datasets which are linked at the individual level with demographic and socioeconomic information.
- This project aims to describe trends over time in prescribing and referrals and identify any differences between groups based on age, sex and area deprivation.
- Please note that these research outputs have not yet been peer-reviewed and should be treated as preliminary.

## Data sources

This analysis used the following data: 

- NHS Grampian subset of the [Prescribing Information System](https://www.isdscotland.org/Health-Topics/Prescribing-and-Medicines/Prescribing-Datamarts/#pis). This is a record of every prescription made or dispensed in the community (i.e. outside of hospitals).
- NHS Grampian CAMHS referrals. Records on referrals inform national reporting of [CAMHS waiting times](https://publichealthscotland.scot/publications/child-and-adolescent-mental-health-services-camhs-waiting-times/child-and-adolescent-mental-health-services-camhs-waiting-times-quarter-ending-31-december-2021/).
- [Scottish Index of Multiple Deprivation 2020 v2](https://www.gov.scot/collections/scottish-index-of-multiple-deprivation-2020/). Linked to place of residence via postcode.
- [Mid-year Population Estimates](https://www.nrscotland.gov.uk/statistics-and-data/statistics/statistics-by-theme/population/population-estimates/2011-based-special-area-population-estimates/population-estimates-by-simd-2016). Officially produced by the National Records of Scotland and broken down by age, sex and SIMD for the calculation of rates.

## Getting started

- Details of the planned analysis for this project can be found in the [Analysis Plan file](https://github.com/HFAnalyticsLab/NDL_CYPMH_Grampian/tree/main/Analysis%20plan)
- Summary data and script files for cleaning and analysis of prescribing and referrals data are found in the [Codes folder](https://github.com/HFAnalyticsLab/NDL_CYPMH_Grampian/tree/main/Codes)
- A summary of the main results of this analysis can be found in the [Report folder](https://github.com/HFAnalyticsLab/NDL_CYPMH_Grampian/tree/main/Report) which contains a written summary and powerpoint presentations.

### Requirements

All script files used for analysis and visualisation were produced using R (version 4.0.3) in RStudio (version 1.4.1103).

## Find out more

Further results from this project are available as a preprint academic article which can be accessed [here](https://www.medrxiv.org/content/10.1101/2022.06.14.22276082v1). Code related to this preprint can also be found in [this associated github repository](https://github.com/AbdnCHDS/NDL_prescribing_referrals_paper).

## Authors

- [Will Ball](https://wpball.com) - [email](mailto:william.ball@abdn.ac.uk) | [GitHub](https://www.github.com/will-ball) | [Twitter](https://www.twitter.com/WillBall12)
- [Jess Butler](https://www.abdn.ac.uk/people/jessicabutler/) - [email](mailto:jessicabutler@abdn.ac.uk) | [GitHub](https://github.com/JessButler) | [Twitter](https://www.twitter.com/JessButler284)

### Acknowledgements

We thank the Health Foundation for providing financial support for this work and the Networked Data Lab group particularly for feedback on planning, analysis and presentation of results. The data used here was collected during the course of healthcare delivery within NHS Grampian and we thank the staff and patients involved. We also thank staff at Grampian Data Safe Haven (DaSH) for processing and making it available for analysis. We are grateful to members of the Aberdeen Centre for Health Data Science Public Involvement group for providing their thoughts on the planning of this project, early reactions to results and interpretations.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
