# UFOs

## Project Overview
We used JavaScript to populate an HTML table with UFO sighting data, and created filter criterias to search through the table to find rows that match user input.

## Results
We first created a [HTML](https://github.com/shahkibria/UFOs_Sightings-JavaScript/blob/main/index.html) webpage which housed the full dataset. The page contains a header and two sections. One section houses the search criterias and the other section houses the table. In the search criteria section, the user can input their required filter criterias the table will update automatically based on that input. In order to reset the table, the user can click the "UFO Sightings" link on the top left corner of the page. A screenshot of what the webpage looks like unfiltered is provided below. 

![](https://github.com/shahkibria/UFOs_Sightings-JavaScript/blob/main/Screenshots/HTML%20-%20Unfiltered.png)

Using the table, the data can be filtered based on the user's perference. For example, if the user wants to filter the data for Date: 1/1/2010 and Shape: "light", the user can input those values in the respective search bars and the data will get filtered based on that preference. A screenshot of the filtered data is provided below. 

![](https://github.com/shahkibria/UFOs_Sightings-JavaScript/blob/main/Screenshots/HTML%20-%20Filtered.png)

## Summary
The table is useful to filter throgh the UFO data based on the user's perference. One drawback of the table is that the data gets filtered automatically right after the user inputs the data. It would have been better if the "Filter Data" button was retained and used as the event listener. Then the data would only get filtered if the button was clicked by the user. 

We can make further improvements to the webpage by adding a "Reset Data" button. This is more intuitive than the user having to click the link on the top of the page to refersh the filters. 
