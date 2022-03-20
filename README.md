# UFOs Sightings - The Truth is Out There

## We are to provide a webpage and working, dynamic table. Our customer would like a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, a set of table filters will be created for the city, state, country, and shape.

## Overview 
ES6+ & Javascript used together can create a powerful tool. Our goal is to understand the strengths and understand the weaknesses, as well as limitations, to reach our clients goals. We will need to use Javascript syntax in ideal locations to deploy built-in functions. Our Javascript loop, or the ForEach loop, will gather the information needed. Our filter components will allow the user interface to narrow in on the information they specifically seek. 

## Results:
### Welcome to UFO Sightings! 

![Pic 1](https://github.com/Baylex/UFOs/blob/main/static/images/top.PNG)

### How the filters appear when first landing on the page:
![Pic 2](https://github.com/Baylex/UFOs/blob/main/static/images/bottom.PNG)

### How the filters appear after being used: 
By typing in the suggested placeholder elements as the filters, the result returns 2 matches.  Make sure to type everything in lower case letters and do not have spaces at the end of the text.  Click off the input box or press enter to initiate the filter.  To reset the filter criteria, click the UFO Sightings at the top left of the website. 

![Pic 3](https://github.com/Baylex/UFOs/blob/main/static/images/working_filters.PNG)


## Summary: 

### Drawback:
The user must know specific dates, cities, or shapes to search.  Some shapes like "light" might not be as intuitive.  The filters require correct lower-case spellings and cannot include spaces at the end.  The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon".  The only acceptable input would be "el cajon".

### Recommendations: 
1. The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.
![Pic 4](https://github.com/Baylex/UFOs/blob/main/static/images/trim.PNG)

2. A filter on a date range might be preferable than a singular date.  Typing 1/2010 did not bring up all the dates from January as hoped.  Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month.  It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings. 

![Pic 5](https://github.com/Baylex/UFOs/blob/main/static/images/date.PNG)
