# UFOs
Module_11

## Project Overview
Assist Dana in enabling her UFO Sightings webpage users the ability to filter for multiple criteria (sighting date, city, state,
country and shape rather than only sighting date) simultaneously.

## Results
Our original webpage provided users the option to filter the sightings table by date only.
![Filter by Date](/Resources/Img-DateOnly.png)

To make the webpage more user friendly and functional, users now have the option to filter by up to five options...Date, City, State, Country and/or Shape.

![Filter by Multiple Options](/Resources/Img_AllFilters.png)

Each filter input area contains a formatted value to provide users with an example of how their text should be entered.  After text is entered and the user hits <Enter> in the various filters, the sightings data table responses update accordingly.

As an example, a user enters the date "1/5/2010" in the Date filter.  The sightings table data is now limited to sightings occurring on 1/5/2010:
![Filter by First Option](/Resources/Img-Filter1.png)

The user decides to limit the table data to one state and enters "nj" in the state filter.  The sightings table data is now limited to sightings occurring on 1/5/2010 and in the state of NJ:
![Filter by Additional Option](/Resources/Img-Filter2.png)

Finally, the user decides to limit the table data by shape and enters "cigar" in the shape filter.  The sightings table data is now limited to sightings occurring on 1/5/2010, in the state of NJ and that are described as cigar-shaped:
![Filter by Additional Option](/Resources/Img-Filter3.png)

The user is able to enter any combination of filter values.  If the user wishes to enter new filter values, they can click the "UFO Sightings" link at the top of the page to reset all filters or refresh the page in their web browser.

![Refresh Page](/Resources/Img-UFOLink.png)

## Summary
#### Drawback
One drawback of the new webpage design is in the location and format of the "UFO Sightings" used to refresh the page and any current filters.  Because of its
white text, it is not obvious to users that this is a link, there is nothing to indicate it should be used to refresh the page and/or reset filters and its 
location is not intuitive for users.

#### Recommendations
- To improve overall usability, I recommend removing the existing "UFO Sightings" link.  A clearly identified button located directly under the existing filters
will be more convenient and recognizable for users.
- If the sightings data is available for scraping, automation of the scraping process will make keeping the sightings data fresh for users relatively simple.
