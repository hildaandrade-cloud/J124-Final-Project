# J124-Final-Project
# The Alameda County Crime Reports Reveal What the Common Offenses are and Where They Occur

## Introduction

Crime data is essential in order for the community to gain a better understanding of patterns in public safety. However, it must be deconstructed carefully with context. In this project, I analyzed the Alameda County Crime Report dataset in order to examine which offenses were most common and which cities recorded the highest number of crime reports.

[Alameda County Sheriff's Office crime reports covering the period July 2022 to present](https://data.acgov.org/datasets/53a54eb59d5f42038e80098384ba5156_2/explore?location=37.693191%2C-121.924887%2C10)


## About the Dataset

This project uses the Alameda County Crime Reports dataset whose data was collected by the Alameda County Sheriff's Office and made available through the Alameda County Open Data Portal.

Since the dataset comes from a government agency it is typically considered a reliable source for documenting reported incidents. The only issue is that only the crime reported through law enforcements are the ones that are recorded. So it doesn't measure crimes that went unreported or does it explain why crimes occurred.

---

## Data Analysis

### Finding 1

![alt text](chart2.jpg)

The most common offense descriptions in the dataset include several warrant-related offenses, drug-related violations, and weapon offenses. These categories appeared more frequently than many other reported offenses.

### Finding 2

![alt text](chart1.jpg)

The city analysis shows that San Leandro, Oakland, Hayward, and Castro Valley account for the largest number of crime reports in this dataset. Population size, policing practices, and reporting activity may all influence these totals.

---

## Methods

I imported the CSV file into Google Sheets and reviewed the data for duplicate headers and missing rows. I created pivot tables to count offense descriptions and cities. I corrected obvious spelling inconsistencies in the City column before creating bar charts to visualize the results.

Google Sheets:
[Alameda County Crime Reports July 2022-Present](https://docs.google.com/spreadsheets/d/14pShk2vxSFuxMdSt-BlYk4zjxVabhrQptHXfskGDG2w/edit?gid=1490871859#gid=1490871859)
---

## Limitations

This dataset only represents crimes reported to law enforcement. Many crimes are never reported, and reporting practices can differ between communities. The data also contains some inconsistent city names and abbreviations, which required minor cleaning. Finally, the dataset cannot explain the causes of crime or measure overall public safety.

---

## Ethical Considerations

Crime statistics can easily be misunderstood if they are presented without context. Higher numbers of reported crimes do not necessarily mean a community is less safe because larger populations and higher reporting rates can produce more reports. Additional reporting, including interviews with local officials and community members, would provide important context beyond the numbers alone.

---

## Conclusion

The Alameda County Crime Reports dataset provides insight into the types of offenses recorded by law enforcement and where those reports occur most frequently. While the data reveals useful patterns, it should be interpreted alongside population, reporting practices, and additional reporting to provide a more complete understanding of public safety.

---

## Sources

- Alameda County Crime Reports dataset
- Alameda County Open Data Portal
- Google Sheets analysis
