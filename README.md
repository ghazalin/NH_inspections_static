# Overdue Nursing Home Inspections: Uninspected and Neglected 
### Nadia Ghazali 

Nursing home inspections play a critical role in publicly-available facility quality measures. In 1998, the Centers for Medicare and Medicaid Services released Nursing Home Compare, a 5-star rating system for every nursing home in the US. These ratings are calculated from nursing home inspections, staffing measures, and largely self-reported clinical measures. Nursing home inspections contribute the largest proportion of this rating, but there is concern over the validity of this data. Due to flatlined federal funding, state survey agencies have struggled to hire and keep enough surveyors to conduct surveys on schedule. And while CMS has provided rigid guidelines for the state inspection process, there are inconsistencies in deficiency counts between otherwise similar states.

I used Python and Altair to generate the images in the brief on overdue nursing home surveys below.

![](images/visualization_screenshot.png)

### Data Sources: 

Provider Information (14,817 rows/102 columns) https://data.cms.gov/provider-data/dataset/4pq5-n9py

This dataset contains information about currently active nursing homes, including their geographic location, number of certified beds, number of average residents, quality ratings, and survey dates, and deficiencies. Each row represents a nursing home.
Health Deficiencies (401,509 rows/22 columns) https://data.cms.gov/provider-data/dataset/r5ix-sfxw

This dataset contains information about nursing home deficiencies over the past three years, including the nursing home, inspection date, citation number, scope and severity, and date of correction. Each row represents a deficiency.
Uninspected and Neglected - 2023 Senate Special Committee on Aging Report https://www.aging.senate.gov/imo/media/doc/UNINSPECTED%20&%20NEGLECTED%20-%20FINAL%20REPORT.pdf

Table 1. Nursing Homes, Certified Beds, and Surveyor Positions, by State FY2022 (52 rows, 5 columns)

This table contains state level information on the number of surveyor positions, the number of nursing homes per surveyor position, and the number of nursing home beds per surveyor position. Each row represents a state.
Table 2: Percent of Vacant Surveyor Positions, by State, 2002 and 2022 (52 rows, 2 columns)

This table contains state level information on the percentage of vacant surveyor positions by state. Each row represents a state.
