# UFOs

## Overview
The purpose of this analysis was to use javascript to create a dynamic HTML webpage that accepts user inputs and adjusts accordingly.  To start off, we built a table to hold and neatly display all of our data on UFO sightings and then we added filters to the table to let users refine their search on more than one level.
## Results
In order to allow users to refine their searches, we created filters for date, city, state, country and shape; users have the ability to utilize as many of these filters as they would like.
![Filters](/filters.PNG)
By entering search criteria into one or more filters, users can refine their searches to find exactly the data they are looking for.
![FiltersInUse](/filtersInUse.PNG)
## Summary
While the dynamic webpage we created allows users to filter through the available data, there are some drawbacks to this webpage in it's current state.  One of the drawbacks of this webpage is that we aren't able to filter on all of the columns in the data table.  To improve this webpage, there are a few things that I recommend be addressed.
- We could clean up the data in the duration column and add another filter to allow users to refine their search based on that criteria.
- We could add another filter for the comments section which would allow users to search the data based on whether or not certain keywords are present in the 'Comments' column.
- In it's current state, the filters for city, state, country and shape are all case sensitive.  These filters could be improved to accept input that is not case sensitive to make the filters more user friendly.