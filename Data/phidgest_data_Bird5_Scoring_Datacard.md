## Repository: 

https://github.com/sammsandoval/calypte-anna

## Dataset Summary: 

.csv dataset containing presence/absence data based off of the phidgets_data_4_2_2024_Trial_1_Bird5.csv in this repository. It is from an Anna's Hummingbird interacting with feeders and perches in captivity for about an hour. But this data focuses on a chunk of 17 minutes and 6 seconds due to time constraints. 

## Languages

English

## Data Instances

A typical datapoint includes the timestamp in "h:m:s" format. It then includes either "1" for presence of a behavior or "0" for absence of a behavior. "Perch" represents perching behavior. This bird only perched on the right perch (reference the phidgets_data_4_2_2024_Trial_Bird5_Datacard.md). "Preen" represents preening, which the bird did not do. "Hover" represents hovering behavior. "Visitation" represents feeding events. Due to time constraints, only times from 11:02:45 AM - 11:19:51 AM are completed.

```json
{
  'Time': Class: chr; '11:07:16 AM',
  'Perch': Class: integer; '0',
  'Preen': Class: integer; '0',
  'Hover': Class: integer; '0',
  'Visitation': Class: number; '1', 
}
```

## Curation Rationale

Feeding sensors and Perch are being tested for accuracy by comparison with manual video scoring. Dataset was created in general for behavioral observation of an Anna's Hummingbird.

## Source Language Producers

Data was produced by a human who manually scored the video. 

## Social Impact of Dataset

This dataset can be used for research on the behaviors of an Anna's Hummingbird species in captivity. Perch data could be assessed for activity levels, such as perching versus flight and visitation for feeding activity.
