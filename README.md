Comparing Sensors to Videography for Behavioral Assessment in Anna’s Hummingbirds (Calypte anna)

Bird ethologists often conduct research by scoring ethograms of direct observations or videos of animals either in the field or captivity. However, video scoring can be time consuming, making long-term behavioral assessment difficult. 
This project aims to develop a method of recording behaviors of Anna’s Hummingbirds (Calypte anna) using affordable small sensors. A cage was constructed consisting of two perches, each attached to a single-point load cell that recorded presence and absence on the perch. 
As hummingbirds typically do not perch on the floor, the amount of time in flight was determined by the time spent off the perch. Four feeders were equipped with infrared beam sensors to record the time and duration of feeding events. 
Sensor data was compared with traditional behavioral scoring. Initial results demonstrate a high level of fidelity between sensors and scored video recordings. 
Certain behaviors could also be associated with specific “signatures” in the scale data, such as preening, suggesting that the perch sensors may be sensitive for measuring activities while perched. This method could reduce the need for human scoring and be applied to many other model species.

This project will create a foundation for the behavioral analyses I will use for my thesis. Fifteen Anna's Hummingbird individuals will be placed under four different photoperiods (daylengths). 
Food will be provided ad libitum, to prevent any effect of food availability. Scaled perches will monitor changes in activity levels and body mass, while feeders outfitted with sensors will monitor feeding frequency and duration. 
Before I can begin monitoring these individuals, I need to test if the sensors I have built will gather accurate data. These sensors should be able to record all these activities without any human interaction.

Hypothesis: Sensor data will be as accurate as video data (i.e there will be no difference between sensor data and video data).

Aim 1: Gather behavioral data and prepare it for R studio

Aim 2: Compare video and sensor data using R studio.

```{r load-packages, message=FALSE}
#Load packages
library(tidyverse)
library(openintro)
library(ggplot2)
```

### Load Data

```{r}
bird17 <- read.csv("phidgets_data_4_24_24_perch_bird17.csv", header = TRUE, stringsAsFactors = TRUE)
```

