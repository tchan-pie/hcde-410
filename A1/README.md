#HCDE410
Files for HCDE410 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data

# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St
**Source:** https://data.seattle.gov/Transportation/.../2z5v-ecg8  (pulled 2026-10-13)
**License / terms of use:** <FILL IN: see below>

## Questions I asked
- When is the trail busiest, and when is it quietest?
- Do cyclists and pedestrians use the trail at different times of day?
- Do people use the trail more on the weekdays or the weekends? If so, what kind of people and at what times of the day?
- Are mornings mostly one direction and evenings the other? 

## How to re-run
1. Download the CSV from the source link above (Export → CSV).
2. Upload it to Google Sheets.
3. Make a pivot table: Rows = Hour, Filter = Weekday/Weekend,
   Values = average of North and South.
4. Insert a line chart and compare the Weekday and Weekend filters.