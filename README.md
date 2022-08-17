# Demo Website for UFO Sightings

## Overview

For this project, we used Javascript to create, fill, and filter a dynamic table on an HTML webpage. This table consists of eye witness accounts of potential UFO sightings, and can be filtered by Date, City, State, Country, and UFO Shape. The filters can be applied individually or together.

## Results

### Step One: Initial View

When the webpage is opened, the user will be greeted with the header and an intro article, as well as the top of the data table. This should match the image below:

<p align ="center">
<img src="https://github.com/bradleywb426/UFOs/blob/main/images/Web1.png" width=800>
</p>
<p align="center">
Fig. 1: Initial view of Webpage
</p>

-----

### Step Two: Initial Data

Scrolling down, the user will then see the table with all filter inputs on the left, as seen in the image below:

<p align ="center">
<img src="https://github.com/bradleywb426/UFOs/blob/main/images/Web2.png" width=800>
</p>
<p align="center">
Fig. 2: Initial view of Table
</p>

-----

### Step Three: Initial Filter

Users can then input a filter for the data to change the output on the table out of the following criteria: Date, City, State, Country, and (UFO) Shape. The effect is demonstrated in the image below, where "light" has been used as an example Shape filter, and shows how the table now only shows sightings of "light" type UFOs. The filter was inputted by typing the desired criteria in all lowercase with no spaces, and the filter is applied when the user either hits the Enter key on their keyboard or by clicking off of the input box.

<p align ="center">
<img src="https://github.com/bradleywb426/UFOs/blob/main/images/Web3.png" width=800>
</p>
<p align="center">
Fig. 3: Example of Initial Filter on Table
</p>

-----

### Step Four: Further Filtering

To showcase the ability to use multiple filters, the "us" (or United States) filter has been applied to the Country input. This doesn't visibly affect the output of the table, and as such more filters will be applied.

<p align ="center">
<img src="https://github.com/bradleywb426/UFOs/blob/main/images/Web4.png" width=800>
</p>
<p align="center">
Fig. 4: "us" Filter added


</p>


Now an additional filter will be applied to the State filter: "ak" (or Alaska). Here we can see the table has now been filtered to display a specific sighting.

<p align ="center">
<img src="https://github.com/bradleywb426/UFOs/blob/main/images/Web5.png" width=800>
</p>
<p align="center">
Fig. 5: "ak" Filter added


</p>

From here, the user can change the filters to find other sightings in the data that they may desire.


## Summary

### Drawback

One drawback of this filter system is the specificity of filters, meaning the user must know how to input the specific filters before filtering. The system woould not intuit that "lights" or "light " is the same as "light"; or that "el cajon", "elcajon", and "el cajon " are supposed to be the same city. 

### Recommendations

Recommendations for further improvements to the website include:

- Potentially changing the filter method from user inputs to become user inputs combined with a dropdown menu of options, allowing users to attempt to search for the filter they're looking for. The dropdown menu could be auto-populated with information from the data, so as to stay up to date with any changes to the data

- An expansion on the Date filter to allow the user to search for all sightings a given day, month, year, or any combination. This allows the user to narrow down their search more even if they only remember part of the date. This also keeps the table easier to search through as more data theoretically gets added to the site in the future.
