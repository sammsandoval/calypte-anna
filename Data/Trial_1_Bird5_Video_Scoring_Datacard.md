## Repository: 

https://github.com/sammsandoval/calypte-anna

## Dataset Summary: 

.csv dataset containing presence/absence data from behavioral scoring of an Anna's Hummingbird interacting with feeders and perches in captivity for about an hour. This dataset correlates to the phidgets_data_4_2_2024_Trial_Bird5.csv in this repository. 

## Languages

English

## Data Instances

A typical datapoint includes the timestamp in "h:m:s" format. It then includes either "1" for presence of a behavior or "0" for absence of a behavior. "Perch" represents perching behavior. This bird only perched on the right perch (reference the phidgets_data_4_2_2024_Trial_Bird5_Datacard.md). "Preen" represents preening, which the bird did not do. "Hover" represents hovering behavior. "Visitation" represents feeding events. Due to time constraints, only times from 11:02:44 AM - 11:19:51 AM are completed. Assume cells without an integer are also "0" or absent of behavior. 

```json
{
  'Time': Class: factor; '11:02:44 AM',
  'Perch': Class: number; '1',
  'Preen': Class: number; '0',
  'Hover': Class: number; '0',
  'Visitation': Class: number; '0', 
}
```

## Curation Rationale

Feeding sensors and Perch are being tested for accuracy by comparison with manual video scoring. Dataset was created in general for behavioral observation of an Anna's Hummingbird.

## Source Language Producers

Data was produced by a human who manually scored the video. 

## Social Impact of Dataset

This dataset can be used for research on the behaviors of an Anna's Hummingbird species in captivity. Perch data could be assessed for activity levels, such as perching versus flight and visitation for feeding activity.
