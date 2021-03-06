# UFOs
Project using JavaScript and Bootstrap.


## Overview of the Project

The aim of the project is to create a website that displays a dynamic table of UFO sightings. The page contains a formula for entering and filtering data. The website was created using HTML for the basic structure and Bootstrap to control the appearance of the site. This website contains a dataset from where users can extract information filtered by various criteria.

## Results

We redesigned the website which originally displayed information based on any random data. Now it allows users to search by criteria based on four more elements: city, state, country, and shape, and use the home button to reload the website.

Here are some results:

First, the Home button (UFO Sightings) has the capability to reload the website and clear the search buttons.

<img width="945" alt="top" src="https://user-images.githubusercontent.com/66500222/178184172-197a81ef-8610-4916-8bd6-e8127764c7fc.png">


Second, The search filter has been updated to include four more elements that can be used independently. 

<img width="938" alt="working_filters" src="https://user-images.githubusercontent.com/66500222/178184679-fd1d76ba-6bc7-4120-b6cc-6c4d71269a6a.png">


Last, since we updated many features there, the information is presented in a clean and organized way.

<img width="944" alt="bottom" src="https://user-images.githubusercontent.com/66500222/178184379-b4082eda-7b38-4bbe-b67f-de1f658e7560.png">

## Summary

The drawbacks of the website included specification in filter search, the user must know specific dates, cities, or shape. Filters require proper lowercase writing and cannot include spaces. For example, the city used could not be entered as "elcajon" or "El Cajon". The only acceptable input would be "el cajon".
Some recommendations for improvement: 
- The next addition to filters should be the addition of a trim function that catches spaces at the end of words and also allows for upper and lower case.
- A date range filter may be preferable to a single date filter. Entering 1/2010 did not result in all January dates as desired. It is possible that UFO sightings occur more often in a particular month than on a particular day of the month. 
