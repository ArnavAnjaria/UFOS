# UFOS

## Overview
This project is an exercise in how to utilize JS and bootstrap elements to create a webpage that is able to pull information from a javascript data file using filters.

## Results
Upon visiting the webpage, the user will see an introduction to the page and with a title using an image of earth from space. 


![Intro Section](/static/images/IntroImg.png)


When they scroll down they will be able to use the filtering tools that we have created. 
They will be able to filter on the following fields:
- Date
- City
- State
- Country
- Shape


![Filtering Section](/static/images/filteredSection.png)


## Summary

A drawback of this page is that the user cannot see the different options for the possible values that can be filtered on. For example, the user would have to know that light is a UFO shape that can be filtered on in order for the filter to be able to narrow down the entries it would show.

Some places for improvement would be:

1. Allowing for non case specific searches. For example in order to search for all UFO sightings in San Diego, the user must type in 'san diego' any uppercase or variation of case will result in no values showing up
2. Ability to sort rather than filter, it may be interesting to see entries based on the duration of sighting, in say descending order.