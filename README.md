# UFOs Sightings - The Truth is Out There

## We are to provide a webpage and working, dynamic table. Our customer would like a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, a set of table filters will be created for the city, state, country, and shape.

## Overview 
ES6+ & Javascript used together can create a powerful tool. Our goal is to understand the strengths and understand the weaknesses, as well as limitations, to reach our clients goals. We will need to use Javascript syntax in ideal locations to deploy built-in functions. Our Javascript loop, or the ForEach loop, will gather the information needed. Our filter components will allow the user interface to narrow in on the information they specifically seek. 

## Reviewing the Search:

- Our base search bar & information is provided as shown below. 
![SearchInfo](https://github.com/ScottyMacCVC/UFOs/blob/main/static/images/Search%20%26%20Info.JPG)

- The search can be initially filtered by a date. The date does severely limit your search because the date has to be exact. We may want to take a look at these items by city or the other options. 
![DateSearch](https://github.com/ScottyMacCVC/UFOs/blob/main/static/images/Date%20Search.JPG)

- The data is likely best searched by city. The reason the city is the best starting place is due to a hierarchy of search tasks. Once the filter is set for say, state, then we have to maintain all searches within the state. Whereas searching by city only allows us to expand our search and move more efficiently through our searches. 
![SearchbyCity](https://github.com/ScottyMacCVC/UFOs/blob/main/static/images/Search%20by%20City.JPG)

![HierarchyIssue](https://github.com/ScottyMacCVC/UFOs/blob/main/static/images/Hierarchy%20Issue.JPG)

- We can extend our search to more exact items such as shape if we are looking for similarities between sightings.  
![ShapeSearch](https://github.com/ScottyMacCVC/UFOs/blob/main/static/images/Search%20by%20Shape.JPG)

### Filtering Conversation: 
The filtering on the page is sort of wonky. Everything has to be perfectly aligned with the data we search. For example, EL Cajon does not provide the data set for "el cajon". Due to capitlization, the search sees these two as different items. The same issue will apply if we type "el cajon ". Notice the extra space at the end of the term. The extra space means the search item differs from the data set. We also need to learn about reseting the search.  To reset the filter criteria, click the UFO Sightings in the top left or clear all search values and hit enter. 


## Summary: 

### Drawback:
The user must know specific dates, cities, or shapes to search.  Some shapes like "light" might not be as intuitive.  The filters require correct lower-case spellings and cannot include spaces at the end.  The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon".  The only acceptable input would be "el cajon".

### Recommendations: 
1. The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.
![Pic 4](https://github.com/Baylex/UFOs/blob/main/static/images/trim.PNG)

2. A filter on a date range might be preferable than a singular date.  Typing 1/2010 did not bring up all the dates from January as hoped.  Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month.  It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings. 

![Pic 5](https://github.com/Baylex/UFOs/blob/main/static/images/date.PNG)
