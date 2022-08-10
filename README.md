# UFOs
Module_11_Javascript_Bootstrap_and_UFOs

## Overview of the analysis:
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, table filters for the city, state, country, and shape are added.

### Purpose of the analysis:
- The list element that creates the button is removed, and there are five list elements for filtering in the index.html file. 
- The event listener is modified to detect changes to each filter in the app.js file.
- The updateFilters() function saves the element, value, and the id of the filter that was changed. 
- The filterTable() function loops through all of the filters and keeps any data that matches the filter values. 
- The webpage filters the table correctly based on user input.

Resources:
Visual Studio Code
JavaScript
HTML, Bootstrap, CSS

## Results:
- Landing page:
The landing page looks like this:
![landing_page](https://github.com/veenapu/UFOs/blob/main/screenshots/landingPage.PNG)

- Single cirteria search:
Make sure to enter the criteria in lower case. Single criteria search should look like this:
![single_criteria_search](https://github.com/veenapu/UFOs/blob/main/screenshots/singleCriteriaSearch.PNG)

- Multi criteria search:
Make sure to enter the criteria in lower case. Multi criteria search should look like this:
![multi_criteria_search](https://github.com/veenapu/UFOs/blob/main/screenshots/multiCriteriaSearch.PNG)

## Summary:

### The drawback of this webpage:
- The limitation of this search is limited data, for what is given in the table.

- The user must use all lower case letters, must know the specific cities, dates, states, duration and shape for searching.

- Some of the shapes listed under the 'shape' column are not intuitive


### Two additional recommendations for further development:
- Multiple options within a search would have been helpful, like being able to choose more than one shape within the 'shape' field, or being able to choose more than one state, etc.,  For ex - Being able to choose two shapes like a circle and light, etc., would be beneficial.
- Expanding the data to a wider search would be beneficial as well.
- It would be helpful to search a date range instead of a single date within the given table.

