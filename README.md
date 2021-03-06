# UFOs Sightings - The Truth is Out There

## We are to provide a webpage and working dynamic table. Our customer would like a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, a set of table filters will be created for the city, state, country, and shape.

## Overview 
ES6+ & Javascript used together can create a powerful tool. Our goal is to understand the strengths and the weaknesses, as well as limitations, of both tool sets to reach our clients goals. We will need to use Javascript syntax in ideal locations to deploy built-in functions. Our Javascript loop, or the ForEach loop, will gather the information needed from the dataset. Our filter components will allow the user interface to narrow in on the information we specifically seek. 

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


## Summary: 

### Filtering Conversation: 
The filtering on the page is sort of wonky. Everything has to be perfectly aligned with the data we search. For example, EL Cajon does not provide the data set for "el cajon". Due to capitlization, the search sees these two as different items. The same issue will apply if we type "el cajon ". Notice the extra space at the end of the term. The extra space means the search item differs from the data set. We also need to learn about reseting the search.  To reset the filter criteria, click the UFO Sightings in the top left or clear all search values and hit enter. 

### Two Recommendations: 
- **1** We should allow more entries to access data with similar information. For example, we can add in a trim function to the search and it should eliminate any extra spaces that may cause search issues. We can do the same thing with a date range instead of a singular date. These would allow a slightly more broad search and help the user. 

- **2** The capitilization issue is by far the lowest hanging fruit. We would want to update our code to allow for any type of capitilization, so long as the root of the term is correct. For example, El Cajon should return el cajon data set. 


## Resources
- Software: Python 3.7.6., VS Code, HTML, Console 
