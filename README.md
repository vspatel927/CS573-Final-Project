# CS 573 Data Visualization Final Project

## Overview
This visualization was created as my final project for WPI's CS 573 - Data Visualization class. The project features a map-based visualization of the 63 United States national parks (as designated by the NPS). The data used to create this visualization includes the name of the park, coordinates of the park's location, and information about the park such as the annual visitor total, date established as a US National Park, and the total land area of the parks. 

The visualization is interactive with features including panning and zooming in and out of the map, hovering over national park locations to see a tooltip with information about the parks, and an alternate view that can be toggled to see a comparison of visitor totals.

## Questions & Tasks

The following tasks and questions were developed to help drive the visualization and interaction decisions for this project:

 * Displaying the locations of national parks
     *  The locations of all 63 parks were mapped using their latitude and longitude to display on the map of the United States and its territories. Using a custom map package developed by Professor Kelleher (geo-albers-usa-territories), the US Virgin Islands and American Samoa, which both contain US National Parks, are also displayed.
 * Showing the most visited national park sites on an annual basis
     * Users can hover over the locations of national parks to see their annual visitor count and year over year change in visitor count from 2022 to 2023. Also, clicking the icon in the bottom right of the visualization toggles an alternate map view, which shows the parks with the most visitors based on the color scale in the top left hand corner.
 * What regions are most national parks located in
     * With all states' boundaries shown, one could deduce that most national parks are located in the western part of the United States, specfically in the states of California, Utah, Colorado, Arizona and New Mexico.

## Project Implementation with Images

[![image](https://github.com/vspatel927/CS573-Final-Project/assets/89553998/99174e49-9dec-428e-a3e8-eaf2f40e3063)](https://vizhub.com/vspatel927/national-parks-map)
The initial map visualization view shown when first opened up, with all 63 parks' locations mapped.

[![image](https://github.com/vspatel927/CS573-Final-Project/assets/89553998/7ec538a6-952f-493e-8b81-327890c7f125)](https://vizhub.com/vspatel927/national-parks-map)
Tooltips appear when you hover over a park's location, giving you information about the number of visitors, year over year visitor change, date established as a national park and total area.

[![image](https://github.com/vspatel927/CS573-Final-Project/assets/89553998/90162953-e85d-4ff2-adda-9df8e889a6c8)](https://vizhub.com/vspatel927/national-parks-map)
The ability to pan and zoom in the map is also added.

[![image](https://github.com/vspatel927/CS573-Final-Project/assets/89553998/20d1f894-2e33-41b4-8355-1893c576ad0d)](https://vizhub.com/vspatel927/national-parks-map)
Clicking the "toggle vistor color scale" icon in the bottom right enables an alternate view of the visualization, where the park locations are colored on a scale based on the number of visitors in 2023.

## Ideas for Future Iterations

  * Adding Leaflet.js to render OpenStreetMap with D3 for a more detailed map view (potentially satellite as well)
  * Adding additional, smaller visualizations to make other pieces of data more easily understandable (charts)
  * Finding ways to classify parks and include more data in the dataset to visualize


