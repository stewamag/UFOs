# UFOs

Analyzing and organizing UFO data that is stored as a JavaScript array.

The finished webpage can be viewed here: 

## Overview of Project: 

The purpose of the project was to create a webpage that could reorganized data stored in a JavaScript array into a searchable table. In order to loop through the data, JavaScript 'forEach' functions were utilized. Filters were added in the HTML file and the JavaScript file rebuilt the table each time the filters were updated. Instead of using a button to update the table once filters were modified, JavaScript was used to 'listen' for input change on the filters.

## Results: 

The webpage allows the user to filter the dataset as desired.

The filters are below:

Each time they are changed, the filters automatically update the table to the right. The functions allow the user to update all fields to filter by multiple points, by just a few, or only one, which makes it quite versatile. 

## Summary:

### Drawbacks:

- The dataset is limited. It would be beneficial to pull sightings from multiple resources to have more of a base to draw on.

- The search is case-sensitive. For example, if the user types 'CA' instead of 'ca' in the "Enter a state" filter, it will filter out all data. See below.

### Recommendations for Further Development:

- The date and shape filters should be a drop-down menu. Unless a user looks through the entire table, they will not know what the options are, so leaving it so open-ended is not helpful.

- The webpage should be constantly scraping for more data and updating itself so that new sightings can be added as the data becomes available.