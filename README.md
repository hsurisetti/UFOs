# UFOs

## Overview of the project
  The overview of the project is to to create a UFO webpage which provides in-depth analysis of UFO sightings that displays dynamic table with UFO sightings in different regions of United States and Canada using Java Script, HTML and CSS. The webpage should have the ability to filter the data based on multple criteria like data, city, state and shape. 

## Features 
 JavaScript (ES6+), BootStrap, HTML, CSS 

## Results
The java script which has been used to meet the criteria for filtering, updating and building the table are shown below. 

- The Table has been built by extracting the data from the <b>data.js</b> file which has all the data in the form of dictionary :

  <img src="https://github.com/hsurisetti/UFOs/blob/main/images/buildTableFunction.png" width=400 />

- Any changes made to the filter has been updated using this function:

    This function essentially creates the filters based on the user inputted value of the corresponding element and value

  <img src="https://github.com/hsurisetti/UFOs/blob/main/images/updateFilterFunction.png" width=400 />
  
-  The Table has been finally fitered using the below functionality:

    The filters are then applied the table by looping all the rows and keeping only the filtered rows, to be sent to build the table with the filtered rows.
 
   <img src="https://github.com/hsurisetti/UFOs/blob/main/images/FilterTableFunction.png" width=400 />
  
 ### UFO Sightings Home page 
 <img src="https://github.com/hsurisetti/UFOs/blob/main/images/HomePage.png" width=400 />
 
 ### UFO Sightings without filters
 <img src="https://github.com/hsurisetti/UFOs/blob/main/images/Homepage_withoutfilters.png" width=400 />
 
 ### UFO Sightings with Date Filter
  <img src="https://github.com/hsurisetti/UFOs/blob/main/images/DateFilter.png" width=400 />

 ### UFO Sightings with Date and shape filter

<img src="https://github.com/hsurisetti/UFOs/blob/main/images/Date_shape_filter.png" width=400 />

### Console output of the filters :

  <img src="https://github.com/hsurisetti/UFOs/blob/main/images/Console_output_filter.png" width=400 />
 
## Summary
Finally, this webpage has been successfully bulit using HTML, CSS and JavaScript. 

### Drawback :
  Some drawbacks which I noticed are 
   - If the user doesn't know the exact date but knows the month that needs to be searched upon, the user cannot search specifically for that month. The user needs to know the exact full date and enter only the full date.
   - Some shapes like 'formation', 'light' , 'fireball' are counter-intutive .
   - Exact spacing needs to be given and cannot include spaces in the end and is case sensitive.

### Recommendations :
My recommendations would be to
 - Provide a data range which looks for all the data within that date range if the user wants to look for any specific month of data
 - Trim the user entered value to remove the spaces at the end and make it case insensitive which would be nice to have feature.
 - Provide a drop-down option for the list of shapes which gives the user with the option to pick a specific shape from that drop-down list.
