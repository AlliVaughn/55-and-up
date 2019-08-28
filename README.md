
# (Team 7: Sam, Deb, Alli)
Recommender will answer this question based on the  questions below:   
In which Austin city quadrant should a 55+ person consider purchasing or renting an Assisted Living Facility residence based on the need for future hospital vists?  
### Research Questions to Answer:
1. What is the average rating of each hospital? 
2. What is the average rating of each ALF? 
3. What is the quad with the highest concentration of hospitals
4. What is the quad with the highest concentration of ALFs
5. Which hospital has the highest number of transports in from EMS


We intend to determine the Assisted Living Facility locations to live nearest to good hospitals in Austin based on the following:   

Data:
Locations of hospitals in Austin ( Google API)
Locations of Assisted living facilities in Austin ( Google API)
Google Ratings of Hospitals in Austin
Google ratings of ALF in Austin (Google API)
<!-- Demographics at hospitals, if possible (% age > 55 admissions)(Need to find these)
Austin Demographics(age, indicating the need to move to these facilities) -->


Determine: 
What hospitals are the best in Austin ( Rating > 4/5 stars) 
Which areas have greatest concentration of Assisted Living Facilities in Austin? ( > x %  or highest tier of data we find. Will split out by % and do city quadrants)


Sources:
Google geo and search by place, Google ratings, Hospital demographics TBD

We can also recommend the need for future ALFs in certain parts of the city based upon the heatmap we produce.



I nitial Class Brainstorm:
We have decided NOT to go with Haversine / distance-based inquiry for Project 1  based on recommendation by Manuel.  

Assisted living facilities = google loc ( L, L )  of ASL facilities ( search api , geo api )
Hospitals = google loc ( L, L )  of ASL facilities ( search api , geo api )
Distance = ALF to Hospitals


#Different marker colors
Loc Map  hospitals ( markers)
Loc Map  ALF( markers)


DF = Distance TO CLOSEST


Heat =  is  ascending [distance r/t ALF ]
Heat map = Heat

Hottest  area is the BEST place to live for a senior looking for a future ALF residence relative to getting quick healthcare.