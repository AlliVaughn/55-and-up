
# Project 1: Assisted Living Recommender
## Team: Sam, Deb, Alli
#### Recommender will answer this question based on the  questions below:   
#### In which Austin city quadrant( NW, NE, SW, SE) should a 55+ person consider purchasing or renting an Assisted Living Facility residence #### based on proximity and rating of hospitals?   

### Research Questions to Answer:
1. What is the average rating of each hospital? 
2. What is the average rating of each ALF? 
3. What is the quad with the highest concentration of hospitals
4. What is the quad with the highest concentration of ALFs
5. Which hospital has the highest number of transports in from EMS


Data:
* Locations of hospitals in Austin ( Google API): get current coordinates
* Locations of Assisted living facilities in Austin (Google API): get current coordinates
* Google Ratings of Hospitals in Austin: get average rating 
* Google ratings of ALF in Austin (Google API): get average rating for TBD time period 
* Austin Texas EMS Transports: get average rating for TBD time period   


## Sources:
* Google geo
* Google search by place 
* Google ratings
* Austin Texas EMS Transport Logs

Determine: 
* Higest rated hospitals in Austin (Rating > 4/5 stars) 
* Highest rated ALFs in Austin?  
* Quadrant with the highest number of ALFs
* Quadrant with the highest number of Hospitals
* Hospitals with highest number of EMS transports


## Visualizations 
Average ALF Rating per facility
Average Hospital Rating per facility
Transports per Hospital Facility 
Layered map of Hospitals and ALFs in Austin 






### Future Scope:  
* Heatmap of distances between Hospitals and ALFs, visualize as heatmap
* recommend the need for future ALFs in certain parts of the city 


<!-- Notes
Initial Class Brainstorm:
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

Hottest  area is the BEST place to live for a senior looking for a future ALF residence relative to getting quick healthcare. -->