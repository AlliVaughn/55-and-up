![MAP](https://github.com/AlliVaughn/Project1/blob/master/final_images/map_snipped.JPG)
# Project 1: Assisted Living Recommender
## Team: Sam, Deb, Alli
#### The problem:  
“The evidence indicates that every additional kilometer [away one is from the hospital] decreases the probability of survival because it causes an injured individual to become a more serious case. She or he will arrive at the hospital in worse condition as the time to reach the emergency room increases. Assessing whether proximity is more or less relevant conditional on the quality or performance of the nearest hospital is an empirical question. Both high‐ and low‐quality hospitals can save both easy and serious cases, but we could expect that, on average, high‐quality hospitals tend to save more of both.” 
Their findings stress that “…poor emergency care services, and low‐quality hospitals increase the importance of hospital proximity.”  - A current study from The Econometrics workshop: The life‐saving effect of hospital proximity

#### We chose to look at both proximity and quality. 

* Aging populations tend to have increasing rates of morbidity, mortality, and long-term sequelae due to delays in treatment such as stroke, organ failure, or heart attack.    

* For this reason, it is an advantage for a person looking for a suitable community to move to due to aging to consider nearby hospital availability and quality.  

* We chose 5 Miles as a radius defining “nearby” medical facilities for the purposes of our inquiry because we are in the United States, and we chose the Google ratings for each facility as a short-term proxy for hospital quality.  


#### Our Recommender will answer this question based on the questions below:   
#### In which Austin city quadrant( NW, NE, SW, SE) should a person consider purchasing or renting an Assisted Living Facility residence based on proximity and rating of hospitals? 

### Project Questions:  
* Where in Austin is the best place to live if one is looking for Assisted Living based on proximity to hospitals and emergency rooms? 
* Where in Austin is the best place to live if one is looking for Assisted Living based on quality of living situation? 
* Where in Austin is the best place to live if one is looking for Assisted Living based on quality of care? 
* Our Recommender: Where in Austin is the best place to live if one is looking for Assisted Living? 

### Research Questions to Answer:
1. What is the average rating of each hospital? 
2. What is the average rating of each ALF? 
3. What is the quad with the highest concentration of hospitals
4. What is the quad with the highest concentration of ALFs


### Data:
* Locations of hospitals in Austin ( Google API): get current coordinates
* Locations of Assisted living facilities in Austin (Google API): get current coordinates
* Google Ratings of Hospitals in Austin: get average rating 
* Google ratings of ALF in Austin (Google API): get average rating for TBD time period  


### Sources:
* Proximity: Google (Place Search, Nearby search)  
* Ratings: Google (Places API)

### Determine: 
* Higest rated hospitals in Austin per quad 
* Highest rated ALFs in Austin per quad  
* Quadrant with the highest number of ALFs
* Quadrant with the highest number of Hospitals
* Recommendation based on findings


### Visualizations 
ALF Ratings per Quadrant
Hospital Ratings per Qudrant
Combined Overview of Ratings for ALFs and Hospitals
Layered map of Hospitals and ALFs in Austin 



### Future Scope:  
* recommend the need for future ALFs in certain parts of the city 


