# dataset_ufo
UFO data scraped from the National UFO Reporting Center website. 

# Source
The data used to create the combined dataset comes from [The National UFO Reporting Center](https://nuforc.org).

# Data
##### _Data Dictionary_
---
| Name | Type | Description |
| ------ | ------ | ----- |
| details | character | the link to the entry as a url |
| date | datetime | the date and time of the sighting |
| city | character | the city the sighting took place in |
| state | factor | the state the sighting took place in |
| country | factor | the country the sighting took place in |
| shape | character | the shape of the ufo |
| summary | character | a description of the sighting details |
| report_date | date | the date the signting was reported |
| posted_date | date | the date the sighting was posted |
| image | boolean | whether an image was taken of the sighting |
---
# Changelog
##### _Project Status:_
11/12/2023: The project is complete. The data was successfully scraped and integrated into a central dataset.

# Notes
This project was a part of an assignment for the class BAIS:3250, or Data Wrangling, at the University of Iowa. 

