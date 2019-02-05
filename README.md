# US_Airports
This page shows a webmap of many of the airports in the US.

When any of the airports are clicked, an interactive popup will appear displaying the city the airport is in and the IATA code for the airport (example: Portland and PDX).

The states are filled according to the number of airports in that state as layed out in the lengend.
The airports are either red if they have a central tower or grey if htyey do not. This symbology is meaningful becuase it helps show areas that have a multitude of small or large airports. For having the most airports out of any state, Alaska's 191 data points are mostly small airports without central towers. This pattern makes sense because each small town needs an airstrip to get supplies in the winter months when the roads are impassable.

I inspected the data in ArcGIS Pro using the convert JSON to Features tool. This allows me to choose the correct fields for querying and pick an appropiate classification for the cloropleth and symbology.

The airport and states data files were obtained through Dr. Bo Zhao at Oregon State University. Basemap was obtained through OpenStreetMap.
This map was compiled on February 2, 2019 by [Cameron Bennett](mailto:bennecam@oregonstate.edu).

I tried to implement both a seach bar and a fullscreen toggle but was unsuccessful on both attempts. :cry:
