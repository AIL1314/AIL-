# uNITAd

This is cara
## About

The purpose of this repository is to distribute handouts during a SESYNC training event. The content changes between short courses, but it typically includes worksheets for different tutorials and any necessary data.

Most trainees will fork this repository during a short course. Following a short course, the content will be archived as a zip file. To get the handouts from a past short course: navigate to [releases](../../releases), select your course by its starting date, and download `handouts.zip`. The zip does not contain a git repository—only the worksheets and necessary data.

## Data

Conflict Database from: UCDP Georeferenced Event Dataset (GED) Global version 17.1 (2016).
Hansen Forest Map: https://earthenginepartners.appspot.com/science-2013-global-forest
CHIRPS: Precipitation data.
Seddon index: VSI. Vegetation Sensitivity Index.

----

`UCDP`

This dataset is UCDP's most disaggregated dataset, covering individual events of organized violence (phenomena of lethal violence occurring at a given time and place). These events are sufficiently fine-grained to be geo-coded down to the level of individual villages, with temporal durations disaggregated to single, individudal days.

csv file

---

'HANSEN'

Trees are defined as vegetation taller than 5m in height and are expressed as a percentage per output grid cell as ‘2000 Percent Tree Cover’. ‘Forest Cover Loss’ is defined as a stand-replacement disturbance, or a change from a forest to non-forest state, during the period 2000–2015. ‘Forest Cover Gain’ is defined as the inverse of loss, or a non-forest to forest change entirely within the period 2000–2012. ‘Forest Loss Year’ is a disaggregation of total ‘Forest Loss’ to annual time scales.

tif format
---

---
'CHIRPS'


Climate Hazards Group InfraRed Precipitation with Station data (CHIRPS) is a 30+ year quasi-global rainfall dataset. Spanning 50°S-50°N (and all longitudes), starting in 1981 to near-present, CHIRPS incorporates 0.05° resolution satellite imagery with in-situ station data to create gridded rainfall time series for trend analysis and seasonal drought monitoring.

Each asset spans a pentad. Each of first 5 pentads in a month have 5 days. The last pentad contains all the days from the 26th to the end of the month.

The dataset contains one band: 'precipitation' (mm/pentad)

---
 'VSI'
Sensitivity of vegetation productivity (defined as EVI) to climate variability (based on temperature, water availability and cloudiness). The index ranges from 0 (low sensitivity, green) to 100 (high sensitivity, red).
---
