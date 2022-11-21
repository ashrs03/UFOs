# UFOs
<img width="173" alt="UFOsighting" src="https://user-images.githubusercontent.com/42523379/202973032-c9f0ee19-cc05-4cdb-826d-2d5ea6d2e764.PNG">

## Overview of Project: 
The purpose of this project is to provide indepth analysis and assist Dana, who has been researching the UFO sightings data, and achieve the end goal of developing  enhanced website so that the user can filter data based on multiple criteria. 

To begin with, the steps involve understanding UFO sighting data that is stored as list or Javascript array. Process steps include understanding the Javascripts functions which are very versatile, writing index.html steps, update the code, work on storyboard building, and develop a dynamic website using the combination of  HTML, CSS and bootstrap grid system that helps to organize a webpage's content into containers, rows, and columns. 

The expectation is that a baseline dynamic website would display a tabular form of data and this can be filtered with search function for date criteria. Once the additional filters are added the UFO sightings data can be filtered based on any of the five criteria or multiplecriterias so that one can get a dynamic view of the UFO sightings data, based on the data file on which the filters are applied. 

## Explain the purpose of this analysis: 

UFO sighting is a facinating topic and has interested the inhabitants on Earth on the extra- terresterial beings and foregin objects that have been sighted in several regions. Dana is researching the data and while the sample data is a defined number of rows and columns, the idea is to apply similar logic in converting Javascript array of data into table and filter the data so that it can be provide more insights on underlying patterns of UFO sightings. 

## Results 

The first step was to create webpage, organize the webpage using bootstrap grid system, use CSS to customize the page, and add functions so that the data is uploaded, and filter is added for 'datetime'.

<img width="923" alt="UFO_Base_File" src="https://user-images.githubusercontent.com/42523379/202973482-3ab08afd-174b-4e3a-8cf1-372b3595778b.PNG">

To add filter based on specific criterias in the data, 4 more rows are added for the list elements. With this one can filter data based on UFO sighting date, city, state, country, and shape for one or multiple criteria 

<img width="948" alt="Filters_Added" src="https://user-images.githubusercontent.com/42523379/202973845-a4804da9-4326-4d7d-82d8-5f3c597d6534.PNG">

The search provides a quick glimpse into the UFO sightings and below are some examples of how the search can be performed for one or more criterias. 

A. City search 

<img width="914" alt="City_Search" src="https://user-images.githubusercontent.com/42523379/202974086-1ad4c291-bc6a-4393-9d89-43a4760955fe.PNG">

B. State search 

<img width="905" alt="State_Search" src="https://user-images.githubusercontent.com/42523379/202974199-637269c5-c0fe-4bce-94f5-dcd3253a4fe3.PNG">

C. Shape search 

<img width="909" alt="Shape_Search" src="https://user-images.githubusercontent.com/42523379/202974263-c0dc86f9-ab22-4de3-b98d-16867edade07.PNG">

D. Multiple criteria search 

<img width="950" alt="MultiCriteria_filter" src="https://user-images.githubusercontent.com/42523379/202974291-75751774-43e2-42c5-847c-59bffb798f58.PNG">

Note that one can use this as a baseline website and html code can be tweaked to add even more criteria and perform similar search across the criterias. 

## Summary: 

Javascript function serves as a useful tool, when it comes to web page design and users can view data in a tabular format along with relevant details within a weblink and use the enhanced filter functions to display the data / analyze it based on the filter criteria. 

In developing the list filters and based on how the code is written, nothing is build to recognize data in Pascal case or in all caps, the search input field requires one to enter data in the same case as defined in the code(snakecase). This would result in users to get no results even when they enter the search criteria correctly but in a different 'case'. This is a major limitation in performing search. 
Secondly, there is no dropdown function so that user can select from dropdown options for search criteria. 

Similarly partial search character entry and dropdown usually makes the search user friendly and also ensures that users are prompted in their search. 

Given that the users have to be mindful of the exact spelling, the case of the words, and also all the possible options one can select, the website built and code is flawed in its assumption of thoroughness of users to perform search. 

In order to further enhance the webpage design: 
1. Adding elements to the code so that the user can type search criteria in any case ( pascal, snake, all caps, all small), allowing partial character entry to perform search, dropdown list to perform search for criterias such as shape( in cases where user may not have knowledge of exhaustive lis tof expected values that would display for the search).
2. Adding more bells and whistles such as not just pulling static data but pulling a live update to data would ensure that the webpage lists to live data updates on UFO sightings. 
3. Allowing key word entry to pull specific records of UFO sightings data based on the 'part word search would be beneficial. 


