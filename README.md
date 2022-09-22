# UFOs

Analyzing and organizing UFO data that is stored as a JavaScript array.

The finished webpage can be viewed here: [UFO Sightings: Fact or Fancy?](https://stewamag.github.io/UFOs)

<img width="1244" alt="Screen Shot 2022-09-21 at 5 48 33 PM" src="https://user-images.githubusercontent.com/106691255/191634744-108da0b4-86ad-4320-9671-3bc07ee48bc1.png">

## Overview of Project: 

The purpose of the project was to create a webpage that could reorganized data stored in a JavaScript array into a searchable table. In order to loop through the data, JavaScript 'forEach' functions were utilized. Filters were added in the HTML file and the JavaScript file rebuilt the table each time the filters were updated. Instead of using a button to update the table once filters were modified, JavaScript was used to 'listen' for input change on the filters.

## Results: 

The webpage allows the user to filter the dataset as desired.

The filters are below:

<img width="271" alt="Screen Shot 2022-09-21 at 5 49 40 PM" src="https://user-images.githubusercontent.com/106691255/191634717-7d316888-c183-44a9-a9fd-fa53dbb62c34.png">

Each time they are changed, the filters automatically update the table to the right. The functions allow the user to update all fields to filter by multiple points, by just a few, or only one, which makes it quite versatile. 

<img width="1238" alt="Screen Shot 2022-09-21 at 5 11 45 PM" src="https://user-images.githubusercontent.com/106691255/191634498-fb0cb9df-d5c1-438e-8248-992ca90cfb7d.png">

<img width="1233" alt="Screen Shot 2022-09-21 at 5 10 46 PM" src="https://user-images.githubusercontent.com/106691255/191634511-407c7bdd-d7d4-427e-8229-6cb9095222e9.png">

## Summary:

### Drawbacks:

- The dataset is limited. It would be beneficial to pull sightings from multiple resources to have more of a base to draw on.

- The search is case-sensitive. For example, if the user types 'CA' instead of 'ca' in the "Enter a state" filter, it will filter out all data. See below.

<img width="1100" alt="Screen Shot 2022-09-21 at 5 20 25 PM" src="https://user-images.githubusercontent.com/106691255/191634531-24188d22-7629-46a4-a8c5-38a545d9e84f.png">

### Recommendations for Further Development:

- The date and shape filters should be a drop-down menu. Unless a user looks through the entire table, they will not know what the options are, so leaving it so open-ended is not helpful.

- The webpage should be constantly scraping for more data and updating itself so that new sightings can be added as the data becomes available.
