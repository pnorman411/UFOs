# UFO Sightings

## Overview of the Project

JavaScript, Bootstrap, and CSS were used to build a dynamic webpage.  A table was created to hold UFO sighting information and table filters were added so users can search by multiple criteria at a time, including by date, city, state, country, and shape.

## Results

The filter search was created so the user can filter on one or more search criteria.  The beginning of the table containing the UFO sighting information is displayed immediately to the right of the search filters.  This display, along with the placeholders in each search field, will aid the user in the format to use and the options available to enter the search criteria.  

![Screenshot](https://user-images.githubusercontent.com/90982811/145758763-f2bd6ef4-25f8-480f-b501-ca377e515842.png)

### Single Criteria Search

Simply enter your search criteria in the box/es and tab to display the results.  Lowercase letters must be used, and the criteria must be exactly as displayed in the table.

The following displays the results for Arkansas by entering "ar" in the State search field.

![AR](https://user-images.githubusercontent.com/90982811/145758787-de4aa158-80cb-4e07-842d-90d400f94681.png)

### Multiple Criteria Search

Multiple criteria can be used at the same time by using 2-5 search fields.  The following displays the results for the state of California and the UFO shape of fireball.

![CA_Fireball](https://user-images.githubusercontent.com/90982811/145758796-5ddc543a-f61a-4422-9827-914476d763cf.png)

## Summary

### Limitations

The search fields do not recognize capital letters, even for state abbreviations.  The date 1/01/2010 will not return any results since the table does not have the zero in the day, so it must be entered as 1/1/2010.  The search entries must match the information exactly as displayed in the table which may lead to inaccurate search results if the user is unaware that they did not enter the criteria exactly as listed in the table.

### Recommendations

To aid in the usability of the search function, I recommend allowing for the use of capitalized letters.  Including drop-down lists within the search fields will also aid users in selecting criteria, otherwise they need to scroll through the table to determine the date range or the types of UFO shapes listed for example.
