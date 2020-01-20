# Saudi Arabia: Traffic Accidents and Casualties Analysis

---

### Overview

The Goal of this project is analyze two data set of number of accidents and number of Licences in Saudi Arabia for all the regions.

---

### Executive Summary

In this project, we have investigated the data were given and saw the patterns of accidents in all regions in Saudi Arabia. Also, defined the factors that affect the accidents percentage and the type of casualties associated with it. We have identified the regions with highest number of licences, accidents, deaths, and injuries.

---
### Datasets

#### Provided Data

For this project, we have two provided datasets:

- [Traffic Accidents and Casualties by Region](./data/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008.csv)

#### dfl description:
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**year**|*object*|2saudi-arabia-driving-licenses-2004-2008.csv|The year in which the licence was issued.| 
|**administrative_area**|*object*|2saudi-arabia-driving-licenses-2004-2008.csv|Region where the licence issued.|
|**driving_licenses**|*object*|2saudi-arabia-driving-licenses-2004-2008.csv|no. of Licences number.|
|**x**|*float*|2saudi-arabia-driving-licenses-2004-2008.csv|Longtitude coordinate|
|**y**|*float*|2saudi-arabia-driving-licenses-2004-2008.csv|Latitude coordinate|


- [Driving Licenses Issued By Administrative Area](./data/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008.csv)

#### dft description:
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**year**|*object*|saudi-arabia-traffic-accidents-2008.csv|The year in which the accident happened.| 
|**region**|*object*|saudi-arabia-traffic-accidents-2008.csv|Region where the accident happen issued.|
|**driving_licenses**|*object*|saudi-arabia-traffic-accidents-2008.csv|Licence number.|
|**indicator**|*object*|saudi-arabia-traffic-accidents-2008.csv| Type of casualty (dead or injured).|
|**value**|*object*|saudi-arabia-traffic-accidents-2008.csv| value that correspond to the type of casualty.|
|**x**|*float*|saudi-arabia-traffic-accidents-2008.csv|Longtitude coordinate|
|**y**|*float*|saudi-arabia-traffic-accidents-2008.csv|Latitude coordinate|

---

### Finding and Recommendations 

##### Among all regions Makkah region has the highest number of accidents, deaths and injuries! 

##### Based on the features given in the data sets, we cannot come up with a more informative analysis. However, it is enough to show us the current situation. As the accidents are inventible, it can be minimized. Strict law enforcement of traffic violations can highly affect the total number of accident and hence decrease the numbers of injuries and deaths. Awareness social campaigns that showcase the injuries and deaths caused by traffic violation also is important to remind people that they must obey the rules and respect the road and the other drives to avoid any loss.
---
### Blog Post
Here is the blog where I summerized my analysis https://medium.com/@azalamri3/saudi-arabia-traffic-accidents-and-casualties-analysis-1a5942b6db52
