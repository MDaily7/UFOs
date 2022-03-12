# JavaScript with UFO's
## Project Overview
The goal of this project was to build a web page with a dynamic table that could be filtered by multiple criteria in order to gain familiarity with JavaScript.
The first step was to build the table in JavaScript with a function; the function appends rows and data to the empty tbody tag within the index.html file. Next, a function
to update the filters was created. The updateFilter function was set up to be called when D3 detected a change in an input field (set up in index.html file); when the change
is detected, the id and value of the filter were saved to an object as key and value pairs and a filterTable function is called. Finally, the filterTable function was built.
The filterTable function sets the default table to be filled with all of the UFO data before filtering the UFO data to display only the rows with values equal to the values 
input into the filters. The final result is a table filled with all of the data built by the buildTable function upon the webpage loading; the table can then be filtered
by specific criteria placed with in the input fields thanks to the updateFilters and filterTable functions. 
## Results
The following images will demonstrate how the filters work to refine the table with specific criteria. In the [Unfiltered Table](), no inputs have been entered and therefore
all of the UFO data is displayed within the table. A single filter can significantly reduce the amount of data being displayed. For example, in the [Oregon UFOs]() table, 
only the state filter is used, but it narrows down the results to just three. Finally, every filter can be utilized to narrow down the table data to a very specific situation
as seen in the [All Filters]() table. 
## Summary
One big drawback of the webpage as it stands is that multiple criteria can't be entered into the same field to filter the table. For example, the table can't be filtered to display
UFO sightings from both California and Oregon at the same time. Developing a way to add more than one value into a filter would add nice functionality to the webpage. Furthermore,
it may be beneficial to add a filter for the Duration column. The data for duration may need to be standardized to make this more useful as the formatting for durations is 
a little eratic, but this could be a nice addition once that was done. 
## Resources
* JavaScript
* [Resources]() folder with images
* [app.js]()
* [index.html]()
* [style.css]() css for webpage styling

