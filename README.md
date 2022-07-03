# UFOs

## Overview

Dana, a data journalist, is given the opportunity to write about her hometown and the infamous UFO sightings that have occurred there throughout the years. She would like to put together a webpage that includes her article, a table of data to support her findings, and the option to use filters to fine tune the results. Using Javascript, we are able to manipulate the data by adding filters for the date, city, state, country, and shape of the sighting and then display the data as a table. Once this is all done, we can incorporate each element of the webpage into a tidy HTML page. 

## Results

The website is designed with ease of use in mind. When you first enter the website, you can see the header "The Truth is Out There" with the article just below it. The table of supporting data can be found with the option to Filter your Search in various ways. 

<img width="1440" alt="Screen Shot 2022-07-03 at 2 16 43 PM" src="https://user-images.githubusercontent.com/101564349/177052310-aa37a928-3fad-4db1-aecb-0e795d5f8552.png">

To Filter your Search, you can input the desired criteria into the "Date" field, the "City" field, the "State" field, the "Country" field, and/or the "Shape" field. As you input your data, the table will automatically update to include any matching results. There is no need to press any button or refresh the page. It should also be noted that you do not need to input criteria into each field. You may input as much or as little criteria as deemed suitable for your desired results. 

<img width="316" alt="Screen Shot 2022-07-03 at 2 20 35 PM" src="https://user-images.githubusercontent.com/101564349/177052416-a8cee1e1-eed8-4662-8997-ebe2f6f76e9d.png">

An example of a filtered search can be seen below with the resulting table:

<img width="1076" alt="Screen Shot 2022-07-03 at 2 25 16 PM" src="https://user-images.githubusercontent.com/101564349/177052545-6955d3ef-3e46-469f-a2a0-2b282a72e15b.png">

## Summary

Although the webpage functions the way Dana needs it to, there are a few drawbacks and improvements that can be made to make it even more user-friendly and overall cleaner and smoother. 

One drawback of this design is: 
* When filtering the data in the 'Filter Search" portion of the webpage, the fields are case-sensitive. Therefore, if someone were to search for a city in all uppercase letters, although the city may be listed in the table, the result will not be returned. 

Two recommendations for further development are:
* Clean up the data that is being used to populate the table. It appears there are some rows that contain encoded text in the "Comments" column. Example pictured below.

<img width="1060" alt="Screen Shot 2022-07-03 at 2 31 41 PM" src="https://user-images.githubusercontent.com/101564349/177052740-0446e3ad-2a4b-4343-9d48-8f08c3b5f792.png">

* Create a dropdown menu for the City, State, Country, and Shape fields so that the user is aware of the available options and does not accidentally type something in wrong or in a different case. 
